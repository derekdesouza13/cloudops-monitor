# CloudOps Monitor

CloudOps Monitor is a cloud infrastructure automation and monitoring platform built using AWS, Terraform, FastAPI, Docker, and GitHub Actions. The project focuses on Infrastructure as Code (IaC), cloud deployment workflows, CI/CD automation, and scalable backend system design.

---

## Features

- AWS infrastructure provisioning using Terraform
- Dockerized FastAPI backend deployment
- CI/CD automation with GitHub Actions
- Real-time health monitoring endpoints
- Scalable backend architecture
- Linux-based cloud deployment workflows
- Infrastructure automation using Infrastructure as Code principles

---

## Tech Stack

### Cloud & DevOps
- AWS EC2
- AWS S3
- AWS IAM
- Terraform
- Docker
- GitHub Actions
- Linux

### Backend
- Python
- FastAPI
- Uvicorn
- AsyncIO

### Monitoring & Infrastructure
- Health-check APIs
- Cloud-ready backend workflows
- Deployment automation pipelines

---

## Project Architecture

Developer Pushes Code
        ↓
GitHub Actions CI/CD Pipeline
        ↓
Terraform Provisions AWS Infrastructure
        ↓
Dockerized FastAPI Application Deployment
        ↓
Cloud Monitoring & Health Checks

## Folder Structure
cloudops-monitor/
│
├── app/
│   ├── main.py
│   ├── requirements.txt
│
├── terraform/
│   ├── provider.tf
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── Dockerfile
├── docker-compose.yml
├── README.md
└── .gitignore

## Getting Started

Clone Repository

git clone https://github.com/YOUR_USERNAME/cloudops-monitor.git
cd cloudops-monitor

## Local Development Setup

Install Dependencies

pip install -r app/requirements.txt

Run FastAPI Server
uvicorn app.main:app --reload

Application URL:
http://127.0.0.1:8000

Health Check Endpoint:

http://127.0.0.1:8000/health

## Docker Setup

Build Docker Container
docker build -t cloudops-monitor .

Run Docker Container
docker run -p 8000:8000 cloudops-monitor

## Terraform Infrastructure Deployment

Initialize Terraform
cd terraform

terraform init
Preview Infrastructure
terraform plan
Deploy Infrastructure
terraform apply

## GitHub Actions CI/CD

This project uses GitHub Actions for:

automated dependency installation
CI/CD workflows
deployment automation
pipeline validation

Workflow file:

.github/workflows/deploy.yml

## Future Improvements

CloudWatch monitoring dashboards
AWS Lambda integrations
Datadog observability
HTTPS with NGINX reverse proxy
Multi-environment Terraform modules
Infrastructure scaling support
Automated rollback pipelines

## Resume Highlights

Built AWS-based infrastructure automation workflows using Terraform and Infrastructure as Code.
Implemented CI/CD pipelines using GitHub Actions for backend deployment automation.
Developed scalable FastAPI backend services with Dockerized deployment workflows.
Designed cloud-ready monitoring and health-check systems for infrastructure observability.

## Author
Derek Frederick Dsouza
LinkedIn: https://linkedin.com/in/derekdesouza1310
GitHub: https://github.com/derekdesouza13