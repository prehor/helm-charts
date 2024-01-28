# Helm Chart: local-storage-class
This is a Helm chart that lets you create a Kubernetes local storage class.

## Install
1. Clone this repository: `git clone https://github.com/prehor/helm-chart`
2. Edit the `./chart/storage/local-storage-class/values.yaml` (optional)
2. Deploy the chart to your Kubernetes cluster: `helm install --name=local-storage ./charts/storage/local-storage-class`

You can check if your storage class have been created by running:
```bash
kubectl get sc
```

## Uninstall
```bash
helm del --purge local-storage
```
