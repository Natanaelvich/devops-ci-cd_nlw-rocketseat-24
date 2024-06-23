# DevOps CI/CD NLW Rocketseat 24

This project is focused on demonstrating Infrastructure as Code (IaC), Continuous Integration/Continuous Deployment (CI/CD), and AWS services.

## Overview

This repository contains a series of scripts and configurations to automate infrastructure provisioning and the CI/CD process using AWS services.

## Prerequisites

- Terraform >= 0.12
- Ansible >= 2.9
- AWS account configured with appropriate credentials
- GitHub Actions configured in the repository

## How to Use

1. **Provision Infrastructure**
   ```bash
   cd terraform
   terraform init
   terraform apply
   ```

2. **Configure Servers**
   ```bash
   cd ansible
   ansible-playbook -i hosts setup.yml
   ```

3. **Run CI/CD Workflows**
   Configure the workflows in GitHub Actions for automatic execution.

## AWS Services Used

- EC2
- S3
- RDS
- IAM

## Contribution

Feel free to open issues and pull requests for improvements and fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

For more information, refer to the documentation in the respective directories or open an issue in this repository.