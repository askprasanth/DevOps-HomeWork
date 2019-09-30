deploy k8s cluster(1 master and 2 worker node) by vagrant in windows 10

# pre-requisite:
Install Vagrant 
oracle Virtual machine

# clone the repo
git clone https://github.com/askprasanth/DevOps-HomeWork.git
cd vagrant k8s deployment
vagrant up

# Install may run for 15 to 20 min

# Once completed login to k8smaster
vagrant ssh k8smaster

# Verifying the cluster
Get Nodes status
kubectl get nodes
Get component status
kubectl get cs

# copy the config to local so that we can do kubectl from local machine
scp vagrant@k8smaster.k8s.com:.kube/config c:/users/prasanth/.kube