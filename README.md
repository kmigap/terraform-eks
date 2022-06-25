# Learn Terraform - Provision an EKS Cluster

This repo is a companion repo to the [Provision an EKS Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-eks-cluster), containing
Terraform configuration files to provision an EKS cluster on AWS.

########################################################################

follow the link bellow for Prerequisites and instructions.

https://learn.hashicorp.com/tutorials/terraform/eks

### go to AWS console and search for eks and get copy the Cluster name
aws eks update-kubeconfig --region us-east-1 --name <add your cluster here>

## or there is a config file that is going to be create when you after terraform apply you can find that there as well.