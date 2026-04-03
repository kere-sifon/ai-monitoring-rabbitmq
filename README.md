# ai-monitoring-rabbitmq

RabbitMQ for log-ingestion and log-processor message bus. Deploys via Bitnami Helm chart.

## Prerequisite

`ai-monitoring-secrets` must exist. Run **ai-monitoring-postgresql** first.

## Quick start

```bash
./deployments/install.sh
```

## Deploy via PR comment

`/deploy aks` or `/deploy openshift` on any PR.
