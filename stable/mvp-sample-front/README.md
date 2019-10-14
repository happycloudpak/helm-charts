
# mvp-sample-front

[mvp-sample-front](https://github.com/happycloudpak/helm-charts/tree/master/stable)
MVP시 참조하기 위한 간단한 상품관리 앱의 front앱입니다.

## Introduction

MVP시 참조하기 위한 간단한 상품관리 앱의 front앱입니다.
mvp-sample-bizlogic앱의 API를 사용하여 수행됩니다.

## Prerequisites

- Kubernetes 1.8+

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ $ helm install <git repository>/mvp-sample-front --name release-mvp-sample-front

```

The command deploys this app on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `release-mvp-sample-front` deployment:

```bash
$ helm delete release-mvp-sample-front --purge
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration
See config.yaml 
Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`. For example,

