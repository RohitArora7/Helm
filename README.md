# Helm

```bash
helm search repo postgre

helm repo add bitnami https://charts.bitnami.com/bitnami

helm repo update

helm status bitnami

helm ls 

helm repo ls

helm install postgresql bitnami/postgresql --set postgresqlPassword=postgres --set postgresqlDatabase=magma 

helm install emcoui . --namespace emco

helm uninstall emcoui
```
