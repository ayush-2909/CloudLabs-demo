# Developer Sandbox Environment – User Guide

## Overview

The Developer Sandbox Environment provides a fully equipped Windows-based development workspace designed for modern software engineering and DevOps workflows.

All required tools, SDKs, cloud CLIs, database engines, and container platforms are preinstalled and configured.

No additional setup is required.

This environment enables you to:

- Build and test applications
- Automate infrastructure deployment
- Work with containers
- Manage cloud resources across Azure and AWS
- Develop and test databases locally
- Practice Infrastructure as Code

---

## Installed Development Stack

### Core Development Platforms

The virtual machine includes industry-standard development tools:

- **Visual Studio 2022 Community**
- **Visual Studio Code**
- **.NET SDK**
- **Node.js (LTS)**
- **Python**
- **OpenJDK 17**
- **PowerShell 7**
- **Git**
- **GitHub CLI**

These tools support backend, frontend, API, scripting, and cross-platform development workflows.

![](images/toolsdevshow.png)

---

## Cloud & Infrastructure Tooling

Multi-cloud development and automation is fully supported.

### Azure Tooling

- Azure CLI  
- Azure PowerShell  
- Azure Storage Explorer  

You can:

- Create and manage resource groups
- Deploy virtual machines
- Manage storage accounts
- Automate infrastructure

---

### AWS Tooling

- AWS CLI  

You can:

- Manage EC2 instances
- Work with S3 storage
- Configure IAM resources
- Automate cloud operations

---

### Infrastructure as Code & Kubernetes

- Terraform  
- kubectl  
- Helm  

These tools enable:

- Infrastructure provisioning in Azure or AWS
- Kubernetes cluster interaction
- Helm chart deployments
- Declarative infrastructure management

---

## Container Development

Docker Desktop is installed and configured.

You can:

- Build container images
- Run containers locally
- Simulate microservices architecture
- Test containerized applications before cloud deployment

---

## Database Development

The environment includes:

- SQL Server Express
- SQL Server Management Studio (SSMS)

You can connect locally using:

Server Name:

localhost

Authentication:

Windows Authentication

This allows you to:

- Create and manage databases
- Execute SQL queries
- Design schemas
- Develop stored procedures

---

## API Development & Testing

Postman is installed for API validation and integration testing.

You can:

- Test REST APIs
- Validate authentication flows
- Debug request/response payloads
- Simulate backend services

---

## Command-Line Utilities

Advanced terminal tools are available for scripting and automation:

- curl
- wget
- jq
- 7zip

These utilities support:

- API testing
- JSON parsing
- File compression
- Command-line data processing

---

## Working with Azure CLI

Open PowerShell 7 or the VS Code integrated terminal.

Run:

az login

After authentication, you can:

- Deploy resources
- Manage networking
- Configure storage
- Automate resource provisioning

---

## Working with AWS CLI

Open PowerShell and run:

aws configure

After configuration, you can:

- Launch EC2 instances
- Upload data to S3
- Manage IAM roles
- Automate AWS workflows

---

## Working with Terraform

Initialize your configuration:

terraform init

Review execution plan:

terraform plan

Deploy infrastructure:

terraform apply

Terraform supports provisioning in both Azure and AWS environments.

---

## Recommended Workflow

A typical development workflow in this environment may include:

1. Develop application code using Visual Studio or VS Code  
2. Manage source control using Git  
3. Containerize the application using Docker  
4. Provision infrastructure using Terraform  
5. Deploy and manage resources using Azure CLI or AWS CLI  
6. Validate APIs using Postman  
7. Store or query data using SQL Server  

This workflow simulates real-world enterprise development environments.

---

## Intended Use Cases

This Developer Sandbox supports:

- Full-stack application development  
- DevOps experimentation  
- Multi-cloud automation  
- Infrastructure as Code practice  
- Container-based deployments  
- Database development  
- Cloud architecture validation  

---

You are now ready to build, automate, deploy, and experiment in a fully configured multi-cloud developer environment.
