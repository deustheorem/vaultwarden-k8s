# vaultwarden-k8s
Helm chart for deploying [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) in Kubernetes.

## TL;DR;

```console
$ helm repo add vaultwarden https://deustheorem.github.io/vaultwarden-k8s/
$ helm install vaultwarden/vaultwarden-k8s
```

OR

```console
$ git clone https://github.com/deustheorem/vaultwarden-k8s
$ cd vaultwarden-k8s
$ helm install ./chart/vaultwarden-k8s
```


## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install --name my-release vaultwarden/vaultwarden-k8s
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

License
=======================================================================

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">vaultwarden-k8s</span> by <a xmlns:cc="http://creativecommons.org" href="https://codewave.eu" property="cc:attributionName" rel="cc:attributionURL">Deustheorem</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

Maintainers
===========

Project is currently maintained, in my spare time!

Forked from: cdwv/bitwarden-k8s