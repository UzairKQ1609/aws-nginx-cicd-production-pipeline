## 📋 Project Overview
An end-to-end cloud infrastructure and automated deployment project designed to simulate a production-grade Junior DevOps Engineer workflow. The architecture establishes a secure AWS infrastructure to host a web application, eliminating manual server updates by triggering an automated CI/CD pipeline on every code push.

## 🛠️ Core Architecture & Technologies
* [cite_start]**Cloud Infrastructure:** AWS EC2 (Ubuntu Linux), IAM (Least Privilege Access Control), AWS VPC [cite: 26, 27, 28, 29]
* [cite_start]**Web Server:** Nginx (Reverse Proxy & Static Content Delivery) [cite: 33]
* [cite_start]**CI/CD Automation:** GitHub Actions / CircleCI [cite: 32]
* [cite_start]**Version Control:** Git & GitHub [cite: 31]

## 🚀 Key Achievements & Workflow
1. [cite_start]**Secure IAM Management:** Engineered programmatic deployment access utilizing strictly scoped IAM policies[cite: 57, 61].
2. [cite_start]**Linux Infrastructure Provisioning:** Launched and configured an AWS EC2 Ubuntu instance, hardening network access via custom Security Groups (SSH on port 22, HTTP on port 80)[cite: 68, 70, 71].
3. [cite_start]**Web Server Deployment:** Provisioned and optimized an Nginx server instance to serve application assets[cite: 86].
4. [cite_start]**Pipeline Automation:** Configured a robust YAML-based workflow to automatically establish an SSH-based deployment to the remote server upon detecting new code commits, achieving zero-downtime updates[cite: 141, 150].
