# Multi-Cloud Virtualized Infrastructure (OpenStack + Virtuozzo)

This project sets up a hybrid multi-cloud infrastructure using OpenStack and Virtuozzo, automated with Terraform and Ansible.

## 🌐 Architecture Overview
- **OpenStack (DevStack)**: Used as the private cloud core.
- **Virtuozzo**: Manages lightweight container-based workloads.
- **AWS Integration**: Simulated hybrid connectivity with cloud VPC.

## 🛠️ Tools Used
- Terraform
- Ansible
- Virtuozzo / OpenStack
- Ubuntu Server
- GitHub Actions (CI/CD)

## 📁 Folder Structure
- `terraform/`: Contains `.tf` files for provisioning.
- `ansible/`: Contains playbooks and roles.
- `scripts/`: Shell scripts for automation.
- `docs/`: Architecture diagrams and screenshots.
- `.github/workflows/`: GitHub Actions CI/CD config.

## ✍️ Author
Enoch Oluwashina Olaleye
