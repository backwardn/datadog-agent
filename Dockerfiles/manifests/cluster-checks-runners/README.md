The kubernetes manifests found in this directory have been automatically generated
from the [helm chart `stable/datadog`](https://github.com/helm/charts/tree/master/stable/datadog)
version 2.3.14 with the following `values.yaml`:

```yaml
datadog:
  processAgent:
    enabled: false
  clusterChecks:
    enabled: true
clusterAgent:
  enabled: true
  metricsProvider:
    enabled: true
clusterChecksRunner:
  enabled: true
```
