# AWS EC2 Instance Setup with Terraform

This project demonstrates how to use Terraform to provision an EC2 instance on AWS. The EC2 instance is configured with a basic security group that allows HTTP and SSH access. 
Additionally, a provisioner is used to output the instance's public IP address to a file.

## Overview

The infrastructure is provisioned using Terraform and includes the following resources:
- **EC2 Instance**: A web server instance running on AWS with a specified AMI and instance type.
- **Security Group**: A security group that allows incoming traffic on ports 80 (HTTP) and 22 (SSH), as well as unrestricted outgoing traffic.
- **Output**: The public IP address of the EC2 instance is written to a local text file.

