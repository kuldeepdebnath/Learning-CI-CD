# CI/CD Pipeline using Jenkins and Ansible on AWS

This project demonstrates a CI/CD pipeline for deploying a static web application on an AWS EC2 instance using Jenkins and Ansible.

---

## 🚀 Project Overview

The pipeline automates deployment using Jenkins and Ansible. Whenever the code is updated, Jenkins executes an Ansible playbook to deploy the latest version to the server.

---

## 🛠️ Tech Stack

- GitHub (Version Control)
- Jenkins (CI/CD Automation)
- Ansible (Configuration Management - YAML Playbooks)
- AWS EC2 (Ubuntu)
- Apache2 (Web Server)

---

## ⚙️ Workflow

1. Code is pushed to GitHub  
2. Jenkins job is triggered manually  
3. Jenkins runs Ansible playbook  
4. Ansible:
   - Installs Apache (if not installed)
   - Copies updated files to server
   - Restarts Apache service  
5. Website is updated on EC2  

---

## 📂 Project Structure
