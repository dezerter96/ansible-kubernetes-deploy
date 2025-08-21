#🚀 Introduction 
This is a clone of the Azure DevOps repository.  
The purpose of this repository is to deploy a Kubernetes cluster to virtual machines running in VirtualBox using Ansible.

#🔨 Getting Started
The intention of this project is to use the Azure DevOps platform to deploy Kubernetes on virtual machines.  
Due to the limited infrastructure (home computer), the project is designed to use the smallest possible hardware resources to enable learning DevOps technologies.

Tools used for the project:
- Azure DevOps
- VirtualBox
- Ansible
- Kubernetes

The main ansible playbook is described in the file **kubernetes.yml**. The file describes the necessary tasks required for correct cluster configuration.  
The file **azure-pipelines.yml** contains a pipeline where the individual steps of the kubernetes cluster building process are described.

# ⎈ Kubernetes cluster
The deployed Kubernetes cluster consists of one master and two nodes. Traffic to individual services can be handled using LoadBalancer.