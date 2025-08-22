## 1. List all Namespaces
```bash
kubectl apply -f yml-apply.yml
```
This command applies the configuration defined in `yml-apply.yml` to create or update resources in the Kubernetes cluster.

```bash
kubectl exec -it nginx-pod -n nginx -- /bin/bash
```
Access the pods

```bash
kubectl describe pod/nginx-pod -n nginx
```

This is describe the pods