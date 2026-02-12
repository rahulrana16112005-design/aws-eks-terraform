# AWS EKS Infrastructure using Terraform

## Overview
This project demonstrates a production-ready Kubernetes infrastructure on AWS EKS using Terraform and Kubernetes.

The focus is on infrastructure design, scalability, and best practices following Infrastructure as Code principles.

## Technology Stack
- AWS (EKS, VPC, IAM)
- Terraform
- Kubernetes
- GitHub

## Repository Structure
- terraform/     : Infrastructure as Code
- kubernetes/    : Kubernetes manifests
- architecture/  : Architecture diagrams
- screenshots/   : Validation screenshots
 
## Infrastructure Validation

Terraform configuration was validated following standard workflow:

- terraform init
- terraform validate
- terraform plan

Screenshots of validation output are available in the screenshots/ directory.

## Kubernetes Workloads

- NGINX Deployment with resource limits
- LoadBalancer Service for external access
- Horizontal Pod Autoscaler for scaling based on CPU usage
