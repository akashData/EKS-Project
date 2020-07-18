Amazon EKS Service: 

Amazon Elastic Kubernetes Service (Amazon EKS) is a fully managed Kubernetes service. Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications

Here we'll create an AWS EKS Cluster and deploy WordPress App on it. We'll create this complete Infrastructure using Terraform.

I've created two terraform codes one for creating complete EKS Cluster and another for deploying our WordPress on it.

Steps To be Followed: 

Here is Terraform to Create AWS EKS Cluster and Deploy Wordpress Infrastructure on it
Pre-requisite

You need Kubectl, Terraform and AWSCLI installed

Login into AWS CLI

You need to login into AWS CLI using "aws configure" command

By default this Code will use Default AWS CLI Profile
If you want to use any other profile then Update Profile in AWS Provider in this code
Run the Code

Create AWS EKS Cluster -

Go inside EKS-Cluster Directory and run the following commands

    terraform init
    terraform apply

Deploying Wordpress -
Go into Infrastructure Directory and run the following commands

    terraform init
    terraform apply

Note :- "terraform apply" command will ask you to approve it in between but you can use "terraform apply --auto-approve" command for auto approval
