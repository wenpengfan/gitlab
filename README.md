# gitlab
k8s环境下搭建gitlab


kubectl create -f gitlab-ns.yml

kubectl create -f gitlab/redis-svc.yml

kubectl create -f gitlab/redis-deployment.yml

kubectl create -f gitlab/postgresql-svc.yml

kubectl create -f gitlab/postgresql-deployment.yml

kubectl create -f gitlab/gitlab-svc-nodeport.yml

kubectl create -f gitlab/gitlab-deployment.yml
