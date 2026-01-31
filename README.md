Terraform EC2 Infrastructure as Code

This project provisions AWS EC2 and Security Groups using Terraform.

Architecture
Terraform → AWS API → EC2 + Security Group

Tech Stack

Terraform

AWS EC2

IAM

Linux

Resources Created

EC2 instance

Security Group (22, 80 open)

Files

main.tf

Steps

Configure AWS credentials

Run terraform init

terraform apply

SSH into EC2

terraform destroy

Learning

Infrastructure as Code

Resource automation

Cloud cost control
