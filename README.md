
# postgres-stateful-application

This will create the PostgreSQL Deployment, Service, PersistentVolumeClaim, Secret, and ConfigMap 
in your Kubernetes cluster.

kubectl apply -f postgres-deployment.yaml

kubectl apply -f postgres-service.yaml

kubectl apply -f postgres-pvc.yaml

kubectl apply -f postgres-secret.yaml

kubectl apply -f postgres-configmap.yaml
