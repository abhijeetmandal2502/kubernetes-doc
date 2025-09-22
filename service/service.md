kubectl get all -n nginx

get all service of namespace of nginx


kubectl port-forward service/nginx-service -n nginx 82:80 --address=0.0.0.0

82 expose to extrnal enviroment

80 port is the kubernate cclustor ip

kubectl get svc,ep -n notes-app
get all service of notes-app