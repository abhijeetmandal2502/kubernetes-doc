## 1. scale pod in deployment
```bash
kubectl scale deployment/nginx-deployment -n nginx --replicas=1
```
This command will help to scale up the deployment of the pods

## 2. get more info of the pods

```bash
kubectl get pods -n nginx -o wide
```
Get more information of the pods