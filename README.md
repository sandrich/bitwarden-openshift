# Bitwarden for OpenShift
Helm chart for deploying [dani-garcia/bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) in OpenShift.

This has been forked from [cdwv/bitwarden-k8s](https://github.com/cdwv/bitwarden-k8s) and adapted to work with OpenShift (or OKD)

## TL;DR;

```console
$ helm repo add bitwarden https://sandrich.github.io/bitwarden-openshift
$ helm install bitwarden/bitwarden-k8s
```

OR

```console
$ git clone https://github.com/sandrich/bitwarden-openshift
$ cd bitwarden-k8s
$ helm install ./chart/bitwarden-openshift
```


## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install --name my-release bitwarden/bitwarden-openshift
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

# License
MIT