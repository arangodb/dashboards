# ArangoDB Grafana Dashboards

This is our repository for sharing ArangoDB [Grafana](https://grafana.com/) dashboards for monitoring
ArangoDB deployments.


| Dashboard  | Scope | Endpoint(s) | Purpose  |
|---|---|---|---|
| [arangodb-overview.json](https://raw.githubusercontent.com/arangodb/dashboards/master/arangodb-overview.json)   |  Nodes, Cluster, Container |  ArangoDB, Node-exporter, Kubelet cadvisor | Basic Cluster Monitoring (3.6) |
| [arangodb-kubernetes.json](https://raw.githubusercontent.com/arangodb/dashboards/master/arangodb-kubernetes.json)   |  Nodes, Cluster, Container |  ArangoDB, Node-exporter, Kubelet cadvisor | Basic Cluster Monitoring (3.7)|
| [dashboard-maintenance.json](https://raw.githubusercontent.com/arangodb/dashboards/master/dashboard-maintenance.json)  |  Cluster, Container | ArangoDB, Kubelet cadvisor | Cluster Maintenance |
| [arangodb_deployment.json](https://raw.githubusercontent.com/arangodb/dashboards/master/arangodb_deployment.json)  |   Nodes, Cluster, Container |  ArangoDB, Node-exporter, Kubelet cadvisor, Kube state metrics | Oasis Cluster Monitoring|


Please refer to [ArangoDB Metrics documentation](https://www.arangodb.com/docs/stable/http/administration-and-monitoring-metrics.html#metrics-api) for more details.

We welcome your take at such dashboards through contributions.
