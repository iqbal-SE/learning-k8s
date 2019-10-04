# K8S cluster Architecture 

In this section, we will discuss the basic structure of the Kubernetes cluster that we will be building, and some of the components that will be part of that cluster.

We will implement three nodes cluster one master and two worker nodes: 
  - Master Node
  - Worker Node 01
  - Worker Node 02

## Tools to install in K8s nodes 
In each of this nodes we will intall list of below tools.
 - Docker : Docker is container run time for Kubernetes to actually execute containers in k8s
 - Kubeadm : Simplifies the process of setting k8s cluster, it basically automates lot of the tasks while setting the cluster, otherwise needed lot of manual steps
 - Kubelet : Basically an agent, manages running containers in each node 
 - Kubectl : Command line tool to interact with cluster 
 - Control Plane : Is a series of different services that forms that K8s Master to control the cluster



  
