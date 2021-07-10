<h1 align="center">A simple example of creating a Kubernetes cluster (with autoscaling)</h1>
This is a repository with an example of deploying applications in a Kubernetes cluster. It has a frontend, a backend and a sample deployment file (YAML file). The deployment includes the ability to auto-scale depending on the load on the application.  

---
## Prerequisites
### 1. Ready kubernetes cluster in one of the clouds (AWS, GCP, etc...)  
See information below 
### 2. Installed and configured [kubectl](https://kubernetes.io/docs/tasks/tools/) 
 

## How to create deploy  
kubectl apply -f ./infrastructure/frontend-service.yaml  
> yaml for backend comming soon   
> scripts for auto deploy in differents os also comming soon

## Project structure
Frontend application (Simple react.js application) - [here](https://github.com/serpis1/kuber-cluster-example/tree/main/frontend)  
Backend application (Simple golang application based on GIN) - [here](https://github.com/serpis1/kuber-cluster-example/tree/main/backend)  
YAML files for deploying in k8s - [here](https://github.com/serpis1/kuber-cluster-example/tree/main/infrastructure)  
Scripts for starting deploy - Comming soon

## How to create k8s kluster
## Google cloud
1. Install [Cloud SDK](https://cloud.google.com/sdk/docs/quickstart)  
2. [Quickstart](https://cloud.google.com/kubernetes-engine/docs/quickstart)

> Set default project - gcloud config set project PROJECT_ID  
> Create cluster in GCP - gcloud container clusters create clusterId  
> Delete cluster in GCP - gcloud container clusters delete clusterId  
> Change "clusterId" to real name id of your cluster

## AWS
Comming soon

## Yandex Cloud
Comming soon