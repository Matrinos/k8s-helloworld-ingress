# k8s-helloworld-ingress
Minimal script for k8s ingress hello world
```
kubectl apply -f ./deployment.yaml
kubectl expose pod helloworld-app --port 8043 --target-port 8043
kubectl apply -f ./ingress.yaml

curl localhost/health
```
