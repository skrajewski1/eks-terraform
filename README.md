# Author: Sean Krajewski
# Date: 6-29-2024
# Purpose: This provision-eks-cluster-with-terraform
This repository helps you provision a cluster in AWS EKS using Terraform.
Expect it to take +12 minutes for Terraform and AWS to create.
Keep in mind the Kubernetes version used (and supported by AWS).

To run use the following commands in order.

terraform init
terraform plan
terraform apply --auto-approve