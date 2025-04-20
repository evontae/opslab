# 🧪 OpsLab: Infrastructure as Code for Logs, Metrics, and Automation

**OpsLab** is a modular, Terraform-powered environment for building, testing, and monitoring cloud infrastructure. It's designed to simulate production-like EC2 behavior with real-time logs, alerts, and automated actions — all without breaking your budget.

---

## 🧰 Tech Stack

- **Terraform** – Infrastructure as Code (IaC) for EC2, Security Groups, IAM, and more
- **AWS EC2** – Virtual instance with CloudWatch integration
- **CloudWatch Agent** – For collecting metrics and custom log files
- **Bash Scripts** – Health checks, simulated logs, and stress tests
- **Git & GitHub** – Version control and documentation

---

## 📦 Features

- ⚙️ **Modular Terraform**: Reusable code for EC2, security groups, IAM
- 🔐 **IAM Role Integration**: Secure access for CloudWatch agent
- 📈 **Metrics & Logs to CloudWatch**: Custom alerts and streaming logs
- 🧪 **Realistic Stress & Log Generators**: Simulated CPU, memory, disk usage
- 🚨 **Custom Health Checks**: Alerts in JSON & log format
- 🧠 **Designed to Practice SRE & DevOps Principles**

---

## 🚀 Getting Started

> _Pre-req: Git, Terraform, AWS CLI, and CloudWatch Agent installed locally_

```bash
git clone git@github.com:your-username/opslab.git
cd opslab
terraform init
terraform plan
terraform apply

