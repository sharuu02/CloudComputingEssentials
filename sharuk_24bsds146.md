# Project Report - Cloud Infrastructure Setup

## Project Overview

This project involves setting up cloud infrastructure for an application. The project includes configuring resources on various cloud platforms (AWS, Azure, GCP), managing infrastructure with Terraform, automating deployments with Ansible, and containerizing applications using Docker.

---

## Table of Contents
1. [Setup and Configuration](#setup-and-configuration)
2. [Cloud Resources Managed](#cloud-resources-managed)
3. [Commands Used](#commands-used)
4. [Backup and Storage](#backup-and-storage)
5. [Conclusion](#conclusion)

---

## Setup and Configuration

- **Cloud Providers**: AWS, Azure, Google Cloud
- **Infrastructure as Code (IaC) Tools**: Terraform, Ansible
- **Containerization**: Docker, Kubernetes

---

## Cloud Resources Managed

- **AWS EC2 Instances**: Provisioning instances using Terraform.
- **Azure Storage**: Configured Blob Storage for backup.
- **GCP Compute Engine**: Managed VMs via Terraform.

---

## Commands Used

Here are the commands I used during the project:

```bash
# Initialize a new Terraform project
terraform init

# Plan the Terraform deployment
terraform plan

# Apply Terraform configuration
terraform apply

# Validate the Terraform configuration
terraform validate

# Create a Docker image
docker build -t my-app .

# Run the Docker container
docker run -d -p 8080:80 my-app

# List files in a tar archive
tar -tzvf cloud_infrastructure_backup.tar.gz

# Compress the cloud_infrastructure directory
tar -czvf cloud_infrastructure_backup.tar.gz cloud_infrastructure/

# Backup cloud resources using zip
zip -r cloud_infrastructure_backup.zip cloud_infrastructure/
