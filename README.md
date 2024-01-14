## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add ocho https://talss89.github.io/ocho-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ocho` to see the charts.

To install the ocho-wordpress chart:

    helm install my-ocho-wordpress ocho/ocho-wordpress

To uninstall the chart:

    helm delete my-ocho-wordpress