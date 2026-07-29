# k8s-configs

my scratch manifests for local minikube experiments.

nothing production-grade — just enough to remember how the pieces fit.

## apply

```
kubectl apply -k base/
kubectl port-forward svc/hello 8080:80
curl localhost:8080
```
