# Project: AWS EKS Infrastructure Automation with Terraform

## Overview
Built reusable Terraform modules for automated provisioning of production-grade AWS EKS clusters for microservices deployment.

## Challenge
Client had manual infrastructure setup taking 2+ days per environment, inconsistent configurations across dev/staging/prod, and no disaster recovery capabilities.

## Solution
- Created modular Terraform code for VPC, EKS cluster, node groups, IAM roles
- Implemented automated CI/CD for infrastructure deployment
- Set up remote state management with S3 + DynamoDB locking
- Documented runbooks for cluster management

## Results
✅ Reduced deployment time from 2 days to 4 hours (50% reduction)  
✅ Achieved consistent infrastructure across all environments  
✅ Enabled infrastructure version control and rollback capabilities  
✅ Reduced configuration errors by 80%  

## Technologies Used
- Terraform
- AWS (EKS, VPC, IAM, EC2, S3)
- Kubernetes
- Helm
- Jenkins

## Architecture
![Architecture Diagram](./architecture-diagram.png)

## Sample Code Structure# eks-terraform-automation
