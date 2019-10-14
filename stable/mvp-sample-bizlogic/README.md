
# mvp-sample-bizlogic

[mvp-sample-bizlogic](https://github.com/happycloudpak/helm-charts/tree/master/stable)
MVP시 참조하기 위한 간단한 상품관리 앱의 backend앱입니다.

## Introduction

MVP시 참조하기 위한 간단한 상품관리 앱의 backend앱입니다.
mvp-sample-front앱을 위해 API를 제공합니다.

## Prerequisites

- Kubernetes 1.8+

## Installing the Chart

To install the chart with the release name `release-mvp-sample-bizlogic`:

```bash
$ $ helm install <git repository>/mvp-sample-bizlogic --name release-mvp-sample-bizlogic

```

The command deploys this app on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `release-mvp-sample-bizlogic` deployment:

```bash
$ helm delete release-mvp-sample-bizlogic --purge
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration
See values.yaml 
Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`. For example,

