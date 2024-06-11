# Uptime-Kuma Helm Chart

This is a Helm Chart for the awesome [Uptime-Kuma](https://github.com/louislam/uptime-kuma) project.
Please be advised that the Helm Chart my not fulfill all needs and is work-in-progress.

## 🚀 Deployment

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add uptime-kuma https://

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo uptime-kuma` to see the charts.

To install the uptime-kuma chart:

    helm upgrade uptime-kuma uptime-kuma/uptime-kuma --install --namespace monitoring --create-namespace

To uninstall the chart:

    helm delete uptime-kuma --namespace monitoring

## ⚙️ Configuration

To get an overview of the configurable and default Values check out the Chart specific [README](./charts/uptime-kuma/README.md).

## 📝 License

[GNU General Public License version 3](./LICENSE)
