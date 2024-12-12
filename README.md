# DevOps Setup Automation Script

This shell script automates the installation of essential DevOps tools and configurations on an Ubuntu-based system. It is designed for DevOps engineers, system administrators, and developers who want to quickly set up a development environment with the most commonly used tools.

## Tools Installed

This script installs the following DevOps tools:

- **Docker** (Containerization platform)
- **Docker Compose** (Define and run multi-container Docker applications)
- **Git** (Version control system)
- **Kubernetes CLI (kubectl)** (Kubernetes command-line tool)
- **Terraform** (Infrastructure as code tool)
- **Ansible** (Automation tool for configuration management)
- **AWS CLI** (Amazon Web Services Command Line Interface)
- **Azure CLI** (Microsoft Azure Command Line Interface)
- **Google Cloud SDK (gcloud)** (Google Cloud Command Line Interface)

Additionally, it configures Docker to run without requiring `sudo` and performs system cleanup after installation.

## Installation Instructions

### 1. Clone the Repository

You can clone this repository using Git:

```bash

git clone https://github.com/vikasjalane/devops-setup.sh.git

```

### 2.Make the Script Executable

Navigate to the directory where the script is located and make it executable:

```bash

cd devops-setup.sh
chmod +x devops-setup.sh

```

## 3. Run the Script

To run the script, use sudo since it requires administrative privileges to install software:

```bash

sudo ./devops-setup.sh




```

## 


