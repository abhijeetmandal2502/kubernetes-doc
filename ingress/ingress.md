 kubectl get ing -n nginx

 kubectl get svc -n ingress-nginx


 kubectl port-forward service/ingress-nginx-controller -n ingress-nginx 8081:80 --address=0.0.0.0