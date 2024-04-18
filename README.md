# sd-exam2
Daniel Jaraba - A00368822

## How to run:

1. Create a cluster with 3 nodes:
```
minikube start --nodes 3 -p cluster-name
```

2. Create namespace:
```
kubectl create namespace namespace-name
```

3. Install helm applications:
```
helm install nginx-app nginx-app/
helm install ubuntu-app ubuntu-app/
```
