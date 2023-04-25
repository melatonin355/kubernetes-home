# kubernetes-home
Kubernetes Stuff for my home server

# Helm Charts
- https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack

## Kube Prometheus 


````
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
helm install kube-prometheus-v1 prometheus-community/kube-prometheus-stack
```
