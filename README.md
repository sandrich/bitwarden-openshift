# Bitwarden for OpenShift
Helm chart for deploying [dani-garcia/bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) in OpenShift.

This has been forked from [cdwv/bitwarden-k8s](https://github.com/cdwv/bitwarden-k8s)

## TL;DR;

```console
$ helm repo add bitwarden https://cdwv.github.io/bitwarden-k8s/
$ helm install bitwarden/bitwarden-k8s
```

OR

```console
$ git clone https://github.com/cdwv/bitwarden-k8s
$ cd bitwarden-k8s
$ helm install ./chart/bitwarden-k8s
```


## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install --name my-release bitwarden/bitwarden-k8s
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

# License
MIT