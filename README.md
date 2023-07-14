# terraform-demo
# Terraform Infrastructure Setup
This repository contains the Terraform code to set up an AWS infrastructure with the following components:

# EC2 instance
Custom VPC with 4 subnets ( 2 Public & 2 Private) <br>
Installation of basic software on the EC2 instance <br>
Attachment of the public subnet to the EC2 instance <br>
Attachment of a role to the EC2 instance with S3 access <br>
Creation of an RDS database <br>
Attachment of the RDS database to the private subnet <br>
Configuration of the RDS database security group to allow access from the EC2 instance <br>
Mapping of the EC2 instance with a Load Balancer <br>

# Prerequisites

Before you begin, make sure you have the following prerequisites set up: <br>

An AWS account with appropriate access permissions <br>
Terraform installed on your local machine

# Usage

**- Clone the repository to your local machine.**
  
git clone https://github.com/caxsolindia/terraform-demo.git

**- Navigate to the repository's directory.**

cd terraform-demo

**- Initialize the Terraform configuration.**

terraform init

**- Apply the Terraform configuration.**

terraform apply

Review the planned changes and enter yes when prompted to proceed with the deployment.

Wait for Terraform to provision the infrastructure. The process may take a few minutes.

Once the deployment is complete, you will find the necessary outputs in the Terraform output.

# Cleaning Up

To remove the infrastructure created by Terraform, follow these steps:

**- Navigate to the repository's directory.**

cd terraform-demo

**- Destroy the Terraform-managed infrastructure.**

terraform destroy






