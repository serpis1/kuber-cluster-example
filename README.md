<h1 align="center">A simple example of creating a Kubernetes cluster</h1>
<h3>Service with two applications (frontend and backend)</h3>

---
## Prerequisites
### Ready kubernetes cluster in one of the clouds (AWS, GCP, etc...)
See information below  


## Project structure
Frontend application (Simple react.js application) - [here](https://github.com/serpis1/kuber-cluster-example/tree/main/frontend)  
Backend application (Golang application based on GIN) - [here](https://github.com/serpis1/kuber-cluster-example/tree/main/backend)  
YAML files for deploying in k8s - [here](https://github.com/serpis1/kuber-cluster-example/tree/main/infrastructure)



## Google cloud
> Create cluster in GCP - gcloud container clusters create clusterId  
> Delete cluster in GCP - gcloud container clusters delete clusterId  
> Change "clusterId" to real name id of your cluster

## AWS
Coming soon