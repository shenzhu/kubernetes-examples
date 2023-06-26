Helm commands

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
helm repo list

helm install monitoring prometheus-community/kube-prometheus-stack
helm list

helm install my-fleetman-release . --set development=true
helm show values .
```