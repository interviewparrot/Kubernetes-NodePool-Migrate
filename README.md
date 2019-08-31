# Google cloud Kubernetes-NodePool-Migrate
This script automates the steps mentioned by 
https://cloud.google.com/kubernetes-engine/docs/tutorials/migrating-node-pool

## Pre-requisites
This script assumes that you have a cluster setup and gcloud is working for the project. Also your kubectl is working pointing the cluster which you plan to migrate.

## Running the script
Once you have the above pre-requisite met you can simply do following steps
1. git clone https://github.com/interviewparrot/Kubernetes-NodePool-Migrate.git
2. `cd Kubernetes-NodePool-Migrate`
3. `sh gcloud-kubernetes-migrating-node-pool.sh CLUSTER_NAME EXISTING_NODE_POOL NEW_NODE_POOL NEW_MACHINE_TYPE NUMBER_OF_NODES`
