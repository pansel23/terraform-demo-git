# Simple Terraform AWS EC2 Project

## Prerequisites
- AWS Account
- GitHub repo with secrets configured

## Workflow
- Push to `main` triggers `terraform plan + apply`
- Pull request triggers validation and plan

## Run locally
```bash
terraform init
terraform plan -var-file="terraform.tfvars"
terraform apply -var-file="terraform.tfvars"
