# cp-schema-registry Helm Chart

> [!NOTE]
> This project is not affiliated with [confluentinc/cp-schema-registry](https://github.com/confluentinc/schema-registry-images).

[cp-schema-registry](https://github.com/devops-ia/cp-schema-registry) is a product to use Apache kafka Schema Registry from [confluentinc/cp-schema-registry](https://github.com/confluentinc/schema-registry-images).

## Usage

Charts are available in:

* [Chart Repository](https://helm.sh/docs/topics/chart_repository/)
* [OCI Artifacts](https://helm.sh/docs/topics/registries/)

### Chart Repository

#### Add repository

```console
helm repo add cp-schema-registry https://devops-ia.github.io/helm-cp-schema-registry
helm repo update
```

#### Install Helm chart

```console
helm install [RELEASE_NAME] cp-schema-registry/cp-schema-registry
```

This install all the Kubernetes components associated with the chart and creates the release.

_See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation._

### OCI Registry

Charts are also available in OCI format. The list of available charts can be found [here](https://github.com/devops-ia/helm-cp-schema-registry/pkgs/container/helm-cp-schema-registry%2Fcp-schema-registry).

#### Install Helm chart

```console
helm install [RELEASE_NAME] oci://ghcr.io/devops-ia/helm-cp-schema-registry/cp-schema-registry --version=[version]
```

## cp-schema-registry chart

Can be found in [cp-schema-registry chart](charts/cp-schema-registry).
