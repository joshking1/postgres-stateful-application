
# postgres-stateful-application

This will create the PostgreSQL Deployment, Service, PersistentVolumeClaim, Secret, and ConfigMap 
in your Kubernetes cluster.

kubectl apply -f postgres-deployment.yaml

kubectl apply -f postgres-service.yaml

kubectl apply -f postgres-pvc.yaml

kubectl apply -f postgres-secret.yaml

kubectl apply -f postgres-configmap.yaml

# Base 64 encoding and decoding

echo -n "Hello, World!" | base64

# Decode

echo -n "SGVsbG8sIFdvcmxkIQ==" | base64 -d
