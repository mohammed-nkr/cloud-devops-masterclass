Cloud and DevOps Engineering Masterclass

Goal: Fast-track transition to Cloud and DevOps Engineering with AI assist.

Phase 1: Core Essentials
- Linux and Terminal: Shell navigation, file management, permissions, SSH, logs, process monitoring.
- Git & GitHub: Version control workflows, branching strategies, merge conflicts, Pull Requests.
- Networking Fundamentals: IP addressing, DNS, ports, HTTP/HTTPS, firewalls, subnets, NAT.

Phase 2: AWS Cloud Core
- Compute & Storage: EC2 instances, S3 buckets, EBS volumes, RDS databases.
- Networking & Security: Custom VPC design, public/private subnets, Security Groups, IAM policies.

Phase 3: Infrastructure as Code (IaC)
- Terraform & AI: Writing HCL code, state management, S3 remote backends, modularizing infrastructure.

Phase 4: Containers & Orchestration
- Docker & Kubernetes: Dockerfiles, image optimization, multi-container setups, Pods, Deployments, Services.

Phase 5: CI/CD Pipelines & Real-World Capstone
- GitHub Actions: Building automated workflows, artifact storage, automated test suite triggers, AWS deployments.
- Capstone Project: Automated deployment of a multi-tier web application using Terraform, Docker, and GitHub Actions.
====================================================================================================
# Linux & Terminal Essentials Cheat Sheet

A quick-reference guide for core Linux commands used in Cloud & DevOps engineering.

## 1. Navigation & File Management
* `pwd` — Print working directory (show where you currently are).
* `ls -la` — List all files in the current directory, including hidden ones, with detailed permissions.
* `cd <directory>` — Change directory.
* `mkdir -p <dir/sub-dir>` — Create a directory (and any necessary parent directories).
* `touch <filename>` — Create a new blank file.
* `cat <filename>` — Display the contents of a file in the terminal.

## 2. Permissions & Ownership
* `chmod +x <filename>` — Make a file executable.
* `ls -l <filename>` — Check file permissions (e.g., `-rw-r--r--`).

## 3. Process Monitoring & System Health
* `top` or `htop` — View real-time system resource utilization (CPU, memory) and active processes.
* `ps aux` — List all running processes across the system.
* `whoami` — Display the username of the currently logged-in user.
