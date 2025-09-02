# AWS Containerized CI/CD Pipeline

## 📌 Project Overview
A fully automated CI/CD pipeline for containerized applications using ECS Fargate, CodePipeline, and Terraform.

## ❗ Problem Statement
The dev team struggled with manual deployments, causing downtime and inconsistent environments.

## 🏗️ Architecture
- Dockerized application deployed on ECS Fargate
- Terraform templates for VPC, ECS, RDS, and IAM
- CodePipeline + CodeBuild for automated deployments
- Secrets stored in AWS Secrets Manager
- CloudWatch logs for monitoring container health

## ✨ Features
- Zero-downtime deployments
- Automated infrastructure provisioning
- Secure secret management
- Continuous integration & delivery

## 🚀 Setup Instructions
1. Clone this repo  
2. Build Docker image and push to ECR  
3. Deploy infra using Terraform  
4. Connect GitHub repo to CodePipeline  

## 🛠 AWS Services Used
ECS, Fargate, CodePipeline, CodeBuild, Secrets Manager, ECR, RDS, Terraform, CloudWatch

## ✅ Outcomes
- Reduced deployment time from hours to minutes
- Standardized environments across dev/stage/prod
- Increased release frequency without downtime
