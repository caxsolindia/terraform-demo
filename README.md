# terraform-demo
# Terraform Infrastructure Setup
This repository contains the Terraform code to set up an AWS infrastructure with the following components:

# EC2 instance
Custom VPC with 4 subnets ( 2 Public & 2 Private)
Installation of basic software on the EC2 instance
Attachment of the public subnet to the EC2 instance
Attachment of a role to the EC2 instance with S3 access
Creation of an RDS database
Attachment of the RDS database to the private subnet
Configuration of the RDS database security group to allow access from the EC2 instance
Mapping of the EC2 instance with a Load Balancer

# Prerequisites

Before you begin, make sure you have the following prerequisites set up:

An AWS account with appropriate access permissions
Terraform installed on your local machine

# Usage

- Clone the repository to your local machine.
  
git clone https://github.com/your/repository.git

- Navigate to the repository's directory.

cd repository

- Initialize the Terraform configuration.

terraform init
