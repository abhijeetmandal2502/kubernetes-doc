  405  kubectl scale deployment/nginx-deployment -n nginx --replicas=1
  406  kubectl get nodes
  407  kubectl debug node/kind-worker
  408  kubectl debug node/kind-worker -it image=ubuntu
  409  kubectl debug node/kind-worker -it --image=ubuntu
  410  ls
  411  cd kubernet/
  412  ls
  413  cd deployment/
  414  ls
  415  cat deployment.yml 
  416  kubectl scale deployment/nginx-deployment -n nginx --replicas=1
  417  kubectl get ts
  418  kubectl get rs
  419  kubectl get rs -n nginx
  420  kubectl scale deployment/nginx-deployment -n nginx --replicas=5
  421  kubectl get rs -n nginx
  422  kubectl rollout restart deployment nginx-deployment -n nginx
  423  kubectl get rs -n nginx
  424  docker pull 985257530282.dkr.ecr.eu-central-1.amazonaws.com/bamboo_be_staging:c446acb1d4656b6d4fc6014e3e33de522b0fa42c
  425  docker login 985257530282.dkr.ecr.eu-central-1.amazonaws.com
  426  aws configure
  427  cd ..
  428  mkdir
  429  mkdir aws
  430  cd aws
  431  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
  432  unzip awscliv2.zip
  433  sudo ./aws/install
  434  aws configure
  435  aws ecr get-login-password --region eu-central-1 | docker login --username AWS --password-stdin 985257530282.dkr.ecr.eu-central-1.amazonaws.com
  436  docker pull 985257530282.dkr.ecr.eu-central-1.amazonaws.com/bamboo_be_staging:c446acb1d4656b6d4fc6014e3e33de522b0fa42c
  437  docker run -d 985257530282.dkr.ecr.eu-central-1.amazonaws.com/bamboo_be_staging:c446acb1d4656b6d4fc6014e3e33de522b0fa42c
  438  docker ps
  439  docker exec -it fec0824c95e8 -
  440  docker ps
  441  docker ps -a
  442  docker logs fec0824c95e8
  443  docker inspect 985257530282.dkr.ecr.eu-central-1.amazonaws.com/bamboo_be_staging:c446acb1d4656b6d4fc6014e3e33de522b0fa42c