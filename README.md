## 📋 Project Overview
An end-to-end cloud infrastructure and automated deployment project designed to simulate a production-grade Junior DevOps Engineer workflow. The architecture establishes a secure AWS infrastructure to host a web application, eliminating manual server updates by triggering an automated CI/CD pipeline on every code push.

---

## 🛠️ Core Architecture & Technologies
* **Cloud Infrastructure:** AWS EC2 (Ubuntu Linux), IAM (Least Privilege Access Control), AWS VPC
* **Web Server:** Nginx (Reverse Proxy & Static Content Delivery)
* **CI/CD Automation:** GitHub Actions / CircleCI
* **Version Control:** Git & GitHub

---

## 🚀 Key Achievements & Workflow
1. **Secure IAM Management:** Engineered programmatic deployment access utilizing strictly scoped IAM policies.
2. **Linux Infrastructure Provisioning:** Launched and configured an AWS EC2 Ubuntu instance, hardening network access via custom Security Groups (SSH on port 22, HTTP on port 80).
3. **Web Server Deployment:** Provisioned and optimized an Nginx server instance to serve application assets.
4. **Pipeline Automation:** Configured a robust YAML-based workflow to automatically establish an SSH-based deployment to the remote server upon detecting new code commits, achieving zero-downtime updates.
