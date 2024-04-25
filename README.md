# cloudbees-kubernetes-demo

## Prerequisites
 Install Kubectl
 Install minikube
 Install docker
 optional install virtualbox(otherwise we can use docker)

## Steps 1
start minikube using minikueb start

## Steps 2
create deployment.yaml and create service.yaml files.
once created using kubectl apply deploy deployment and services

## Steps 3
once service created using minikube ssh logged into cluster and verified nginx app up.
to access form browser use below command  
# minikube service nginx-service --url

## Steps 4
create helm template using the helm create chart command

## Steps 5
once created the helm chart insatlled and in the browser got the final nginx welcome page.

![image](https://github.com/priyamathavan/cloudbees-kubernetes-demo/assets/129311665/d1181c92-1a4b-4c0b-89b8-ff9288a765a8)







 
