# Ansible role - `k8s_metrics-server`

Manage metrics-server on Kubernetes clusters.

## Tags

| Tag      | Description           |
|----------|-----------------------|
| `apply`  | Deploy Metrics Server |
| `delete` | Remove Metrics Server |

## Variables

| Variable                    | Type     | Required | Default | Description                      |
|-----------------------------|----------|----------|---------|----------------------------------|
| `k8s_metricsserver_version` | `string` | No       | `0.3.7` | Metrics Server version to deploy |


## Templates

| Template                    | Description                                |
|-----------------------------|--------------------------------------------|
| `components-<x.y.z>.yml.j2` | Metrics Server manifest in version `x.y.z` |
