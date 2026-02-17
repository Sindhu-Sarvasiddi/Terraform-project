Production-Ready Infrastructure Deployment using Terraform on AWS

Project Summary

Designed and deployed a cloud-based web application infrastructure on AWS using Terraform (Infrastructure as Code).

Provisioned a complete networking stack (VPC, Subnet, Internet Gateway, Route Table, Security Groups) and deployed a Flask application on an EC2 instance running Ubuntu.

This project demonstrates practical experience in:

Infrastructure as Code (IaC)

AWS networking

Linux server management

Python application deployment

Cloud security configuration

Using Terraform, this project:

Creates a VPC

Creates a Subnet

Creates an Internet Gateway

Configures Route Tables

Creates a Security Group

Launches an EC2 instance

Installs Python & Flask

Deploys and runs a Flask application on Port 80

The Flask app is accessible via the EC2 Public IP.

Terraform Provisioners Used

This project uses Terraform provisioners to automate application setup after EC2 creation.

🔹 file Provisioner

Transfers application code (app.py) from local machine to EC2 instance.

🔹 remote-exec Provisioner

Executes remote commands to:

Update Ubuntu packages

Install Python dependencies

Create virtual environment

Install Flask

Run Flask application on Port 80

Networking & Security Concepts Implemented :

Public subnet internet routing

Security Group inbound rules (22, 80)

Binding Flask to 0.0.0.0

Linux privileged port handling

Public IP exposure and testing

Highlights

Automated AWS infrastructure provisioning using Terraform

Implemented remote-exec and file provisioners for application bootstrap

Configured secure networking and internet routing

Deployed Python web application in cloud environment

Troubleshot Linux permission and environment isolation issues
