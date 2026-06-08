# Kubernetics_Minikube
# Kubernetes Minikube MongoDB Application

## Technologies
- Kubernetes
- Minikube
- MongoDB
- Docker

## Architecture
Web Application --> Service --> MongoDB Service --> MongoDB Pod

## Features
- MongoDB deployment
- Internal service communication
- ConfigMaps and Secrets
- NodePort exposure

## How to Run

kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml
