# AWS EBS CSI Driver Integration with EKS Cluster

The AWS EBS CSI Driver enables Kubernetes to manage Amazon EBS volumes seamlessly through Persistent Volumes (PVs) and Persistent Volume Claims (PVCs).

This repository contains the Terraform configurations to integrate the AWS EBS CSI Driver with an existing AWS EKS cluster. It includes the setup of necessary IAM roles, policies, and attachments, encryption for EBS volumes, and the association of the EKS cluster with the CSI Driver role. Additionally, a StatefulSet is provided for demonstration purposes.

## Key Features:
- Seamless management of Amazon EBS volumes in Kubernetes using the EBS CSI Driver.
- Configuration of IAM roles and policies for secure operation.
- Support for encrypted EBS volumes.
- Deployment of the AWS EBS CSI Driver addon in the EKS cluster.
- Demonstration of StatefulSet deployment with persistent storage.

## Prerequisites:
- An existing EKS cluster.

## Resources Configured:
- IAM Policies and Roles for the EBS CSI Driver.
- EBS volume encryption policies.
- EKS Pod Identity Association for the CSI Driver.
- AWS EKS Addon for the EBS CSI Driver.

This setup simplifies the dynamic management of EBS volumes within Kubernetes clusters, enhancing the capabilities and security of your EKS environment.