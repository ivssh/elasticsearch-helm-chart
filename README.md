# Elastic Cloud on Kubernetes Helm Chart

This functionality is in beta and is subject to change. The design and code is less mature than official GA features and is being provided as-is with no warranties. Beta features are not subject to the support SLA of official GA features.

## Requirements

* [Helm](https://helm.sh/) >= 2.8.0
* Kubernetes >= 1.8

### Elasticsearch

| Parameter                  | Description                                                                                                                                                                                                                                                                                                                | Default                                                                                                                   |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| `version`              | The Elasticsearch version to use | `7.1.0` |
| `nodeCount`            | How many pods to create          | `1`     |

### Kibana

| Parameter                  | Description                                                                                                                                                                                                                                                                                                                | Default                                                                                                                   |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| `version`              | The Kibana version to use | `7.1.0` |
| `nodeCount`            | How many pods to create          | `1`     |
