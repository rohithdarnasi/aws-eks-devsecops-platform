# AWS EKS DevSecOps Platform

## Project Overview

This project demonstrates the implementation of a complete DevSecOps platform on AWS using Infrastructure as Code, CI/CD, GitOps, Security Scanning, Monitoring, and Kubernetes.

The platform provisions AWS infrastructure using Terraform, deploys containerized applications on Amazon EKS, automates CI/CD using Jenkins, performs code quality and security checks, manages deployments through ArgoCD, and provides monitoring through Prometheus and Grafana.

---

## Application Stack

### Frontend

* React.js

### Backend

* Node.js
* Express.js

### Database

* MongoDB

---

## DevOps Stack

* AWS EKS
* AWS ECR
* Terraform
* Jenkins
* Docker
* Kubernetes
* ArgoCD
* SonarQube
* Trivy
* AWS Load Balancer Controller
* Prometheus
* Grafana

---

## Architecture

GitHub

↓

Jenkins Pipeline

↓

SonarQube Analysis

↓

Trivy Security Scan

↓

Docker Build

↓

AWS ECR

↓

ArgoCD

↓

Amazon EKS

↓

AWS Application Load Balancer

↓

Application

↓

Prometheus + Grafana

---

## Features Implemented

### Infrastructure as Code

Provisioned using Terraform:

* VPC
* Public Subnets
* Private Subnets
* NAT Gateway
* Route Tables
* Security Groups
* EKS Cluster
* Managed Node Groups

---

### Continuous Integration

Jenkins Pipelines:

* Infrastructure Pipeline
* Frontend Pipeline
* Backend Pipeline

Pipeline Stages:

* Source Checkout
* SonarQube Analysis
* Quality Gate Validation
* Trivy File Scan
* Docker Image Build
* AWS ECR Push
* Kubernetes Manifest Update

---

### Security

SonarQube

* Static Code Analysis
* Code Quality Validation

Trivy

* File System Scanning
* Container Image Scanning

---

### GitOps

ArgoCD was configured for:

* Frontend Deployment
* Backend Deployment
* Database Deployment
* Ingress Deployment

Benefits:

* Continuous Synchronization
* Automated Deployments
* Rollback Capability
* Git as Source of Truth

---

### Monitoring

Prometheus

* Metrics Collection
* Node Monitoring
* Cluster Monitoring

Grafana

* Dashboard Visualization
* Infrastructure Monitoring

---

## Challenges Solved

During implementation the following issues were identified and resolved:

* Terraform Backend Configuration Errors
* Terraform Version Compatibility Issues
* Jenkins Tool Installation Problems
* AWS Load Balancer Controller CrashLoopBackOff
* IAM Service Account Configuration Issues
* ECR Authentication Failures
* Kubernetes ImagePullBackOff Errors
* ArgoCD Synchronization Problems
* Grafana Exposure Configuration
* Prometheus Deployment Issues

---

## Learning Outcomes

* AWS EKS Administration
* Infrastructure as Code
* Kubernetes Operations
* CI/CD Pipeline Design
* GitOps Workflows
* Container Security
* Monitoring and Observability
* Production Deployment Practices

---

## Screenshots

Implementation screenshots are available in the screenshots folder.

---

## Author

Rohith Darnasi

Cloud | DevOps | Kubernetes | Platform Engineering
