# AWS Infrastructure Setup Using Terraform

This project demonstrates how to automate the provisioning of AWS cloud infrastructure using Terraform. It creates a fully functional environment consisting of a VPC, public subnets, EC2 instances, an internet gateway, route tables, and an S3 bucket — all using Infrastructure as Code (IaC) principles.

---

## Components Provisioned

- Custom Virtual Private Cloud (VPC) — 172.16.0.0/16  
- Two Public Subnets — 172.16.1.0/24 and 172.16.2.0/24  
- Two EC2 Instances (1 per subnet)  
- Internet Gateway (IGW) for public access  
- Route Tables and associations  
- S3 Bucket (for object storage or Terraform backend)  

---

## Deployment Steps

Make sure Terraform and AWS CLI are installed and configured.

1. Clone the repository:

   ```bash
   git clone https://github.com/Sujal-SM/terraform-aws-infra-automation.git
   cd terraform-aws-infra-automation


## Terraform command

- terraform init         # Initialize the working directory
- terraform validate     # Validate configuration files
- terraform fmt          # Format code for consistency
- terraform plan         # Show the execution plan
- terraform apply        # Apply the configuration
- terraform output       # View output values
- terraform show         # (Optional) Show current state
- terraform destroy      # (Optional) Destroy the infrastructure



