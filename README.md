# Terraform Mini Project

A learning project focused on AWS infrastructure deployment using Terraform. This project is inspired by a Pluralsight course but modified with my own learning goals.

## Project Overview
This project sets up a basic AWS infrastructure including:
- VPC configuration
- EC2 instances
- Security groups
- Network configuration

## Prerequisites
- AWS Account
- Terraform installed
- AWS CLI configured
- Basic understanding of AWS services

## AWS Environment Setup
- Region: us-east-1 (default)
- Required Services:
  - EC2
  - VPC
  - IAM

## Getting Started
1. Clone this repository
2. Configure AWS credentials using `aws configure`
3. Initialize Terraform:
  ```
    terraform init
  ```
4. Create a plan:
  ```
  terraform plan -out m3.tfplan
  ```
6. Apply the infrastructure:
  ```
  terraform apply m3.tfplan
  ```
# Security Note
- Never commit AWS credentials to Git
- Use environment variables or AWS CLI configuration for credentials
- Enable 2FA for AWS accounts

# Resource Management 
To destroy all resources:
  ```
  terraform destroy
  ```
# Learning Journey 
This project represents my learning journey with Terraform and AWS infrastructure as code.