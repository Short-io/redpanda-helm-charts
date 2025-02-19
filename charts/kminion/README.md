---
title: Redpanda Kminion Helm Chart Specification
tags:
  - Kubernetes
  - Helm configuration
description: The most popular Open Source Kafka JMX to Prometheus tool by the creators of [Redpanda Console](https://github.com/redpanda-data/console) and Redpanda
---

![Version: 0.12.0](https://img.shields.io/badge/Version-0.12.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: v2.2.5](https://img.shields.io/badge/AppVersion-v2.2.5-informational?style=flat-square)

This page describes the official Redpanda KMinion Helm Chart. In particular, this page describes the contents of the chart’s [`values.yaml` file](https://github.com/redpanda-data/helm-charts/blob/main/charts/kminion/values.yaml). Each of the settings is listed and described on this page, along with any default values.

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)

## Source Code

* <https://github.com/redpanda-data/helm-charts>

## Settings

### [affinity](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=affinity)

**Default:** `{}`

### [autoscaling.enabled](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=autoscaling.enabled)

**Default:** `false`

### [autoscaling.maxReplicas](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=autoscaling.maxReplicas)

**Default:** `100`

### [autoscaling.minReplicas](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=autoscaling.minReplicas)

**Default:** `1`

### [autoscaling.targetCPUUtilizationPercentage](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=autoscaling.targetCPUUtilizationPercentage)

**Default:** `80`

### [customLabels](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=customLabels)

**Default:** `{}`

### [daemonset.enabled](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=daemonset.enabled)

**Default:** `false`

### [deployment.annotations](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.annotations)

**Default:** `{}`

### [deployment.env.configMapKeyRefs](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.env.configMapKeyRefs)

**Default:** `[]`

### [deployment.env.secretKeyRefs](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.env.secretKeyRefs)

**Default:** `[]`

### [deployment.env.values](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.env.values)

**Default:** `[]`

### [deployment.extraContainers](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.extraContainers)

**Default:** `{}`

### [deployment.initContainers](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.initContainers)

**Default:** `{}`

### [deployment.labels](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.labels)

**Default:** `{}`

### [deployment.readinessProbe.enabled](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.readinessProbe.enabled)

**Default:** `true`

### [deployment.volumes.extra](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.volumes.extra)

**Default:** `[]`

### [deployment.volumes.secrets](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=deployment.volumes.secrets)

**Default:** `[]`

### [fullnameOverride](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=fullnameOverride)

**Default:** `""`

### [image.pullPolicy](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=image.pullPolicy)

**Default:** `"IfNotPresent"`

### [image.repository](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=image.repository)

**Default:** `"redpandadata/kminion"`

### [image.tag](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=image.tag)

**Default:** `""`

### [imagePullSecrets](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=imagePullSecrets)

**Default:** `[]`

### [ingress.annotations](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.annotations)

**Default:** `{}`

### [ingress.enabled](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.enabled)

**Default:** `false`

### [ingress.extraPaths](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.extraPaths)

**Default:** `[]`

### [ingress.hosts[0]](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.hosts[0])

**Default:** `"chart-example.local"`

### [ingress.labels](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.labels)

**Default:** `{}`

### [ingress.path](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.path)

**Default:** `"/"`

### [ingress.pathType](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.pathType)

**Default:** `"Prefix"`

### [ingress.tls](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=ingress.tls)

**Default:** `[]`

### [kminion.config](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=kminion.config)

**Default:** `{}`

### [nameOverride](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=nameOverride)

**Default:** `""`

### [nodeSelector](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=nodeSelector)

**Default:** `{}`

### [podAnnotations](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=podAnnotations)

**Default:** `{}`

### [podDisruptionBudget.maxUnavailable](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=podDisruptionBudget.maxUnavailable)

**Default:** `1`

### [podSecurityContext.fsGroup](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=podSecurityContext.fsGroup)

**Default:** `99`

### [podSecurityContext.runAsUser](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=podSecurityContext.runAsUser)

**Default:** `99`

### [replicaCount](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=replicaCount)

**Default:** `1`

### [resources](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=resources)

**Default:** `{}`

### [securityContext.allowPrivilegeEscalation](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=securityContext.allowPrivilegeEscalation)

**Default:** `false`

### [service.annotations](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=service.annotations)

Annotations to add to the service

**Default:** `{}`

### [service.extraPorts](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=service.extraPorts)

The extraPorts can be used to make discoverable ports for Prometheus ServiceMonitors

**Default:** `[]`

### [service.port](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=service.port)

The port for kminion metrics endpoint

**Default:** `8080`

### [service.type](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=service.type)

**Default:** `"ClusterIP"`

### [serviceAccount.annotations](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceAccount.annotations)

**Default:** `{}`

### [serviceAccount.create](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceAccount.create)

**Default:** `true`

### [serviceAccount.name](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceAccount.name)

**Default:** `""`

### [serviceMonitor.additionalLabels](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceMonitor.additionalLabels)

**Default:** `{}`

### [serviceMonitor.create](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceMonitor.create)

**Default:** `false`

### [serviceMonitor.honorLabels](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceMonitor.honorLabels)

**Default:** `false`

### [serviceMonitor.interval](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceMonitor.interval)

**Default:** `"15s"`

### [serviceMonitor.relabelings](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceMonitor.relabelings)

**Default:** `[]`

### [serviceMonitor.scrapeTimeout](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=serviceMonitor.scrapeTimeout)

**Default:** `"10s"`

### [tolerations](https://artifacthub.io/packages/helm/redpanda-data/redpanda?modal=values&path=tolerations)

**Default:** `[]`

