# Grafana-provisioning

Setting the paths.provisioning property in the main config file:
```
[paths]
provisioning = <path to config files>
```
The provisioning directory assumes the following structure:
```
provisioning/
├── alerting
├── dashboards
├── datasources
├── notifiers
└── plugins

```
>Note: The provisioning directory contains configuration files that are applied whenever Grafana starts and continuously updated while running.

