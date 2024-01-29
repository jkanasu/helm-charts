# helm-charts
A repository of useful helm charts 

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add jagi https://jkanasu.github.io/helm-charts

To retrieve the latest versions of the packages, run:

    helm repo update

To see the charts, run:

    helm search repo jagi

To install the busybox chart:

    helm install my-busybox jagi/busybox

To uninstall the chart:

    helm delete my-busybox