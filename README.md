# bitwarden-k8s
Helm chart for deploying [dani-garcia/bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) in Kubernetes.

## TL;DR;

```console
$ git clone https://github.com/tinoschroeter/bitwarden-k8s
$ cd bitwarden-k8s
$ helm install bitwarden ./chart/bitwarden-k8s -f values.yaml
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
