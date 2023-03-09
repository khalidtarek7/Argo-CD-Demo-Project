# Deploying EKS Cluster using Terraform and deploying a Node.js app using Argo CD
This repository contains the Terraform configuration files to deploy an Amazon EKS cluster on AWS and the files required to deploy a Node.js app using Argo CD.
# Prerequisites:
Before deploying the EKS cluster and deploying the Node.js app using Argo CD, you will need:

    - An AWS account with appropriate permissions to create EKS clusters and IAM roles.
    - An AWS CLI installed on your machine.
    - A Kubernetes command-line tool, such as kubectl.
    - A Git repository for storing the application code.
    
```bash
In this project, I used Terraform to deploy an Amazon EKS cluster on AWS. Once the cluster was up and running, I leveraged the power of Argo CD to deploy a Node.js app onto the Kubernetes cluster. With Argo CD's GitOps approach, managing and deploying applications to the EKS cluster became a seamless experience. 
```
