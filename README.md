# 🏗️ Terraform AWS Free Tier Lab

A hands-on lab using **Terraform** to provision AWS infrastructure within the **Free Tier** limits. This project is designed to demonstrate basic infrastructure-as-code (IaC) skills, reusable modules, and deployment automation practices.

---
## 📌 Table of Contents

- [Features](#Features)
- [Technologies Used](#Technologies-Used)
- [Setup Instructions](#Setup-Instructions)
- [Project Structure](#Project-Structure)
- [Resources](#Resources)
- [Author](#Author)
  
---
## 🚀 Features

- ✅ Create VPC, Subnets, Internet Gateway, Route Tables
- ✅ Provision EC2 instance (Amazon Linux 2)
- ✅ Attach Security Groups and Key Pairs
- ✅ Create an S3 bucket
- ✅ Use remote state with Terraform backend (optional)
- ✅ Written with Free Tier limits in mind

---
## 💻 Technologies Used

- [Terraform](https://www.terraform.io/)
- [AWS](https://aws.amazon.com/free/)
- [GitHub](https://github.com/)
- CLI tools: `aws-cli`, `terraform`

---

## ⚙️ Setup Instructions

1. Clone the repo  
   ```bash
   git clone https://github.com/girishpotdar/terraform-aws-free-tier-lab.git
   cd terraform-aws-free-tier-lab

2. Configure AWS Credenetials
   ```bash
   aws configure

3. Initialize and apply Terraform
   ```bash
   terraform init
   terraform plan
   terraform apply

4. Destroy resources when done
   ```bash
   terraform destroy

------
## 📁 Project Structure


```bash
terraform-aws-free-tier-lab/
│
├── main.tf            # Core resources
├── variables.tf       # Input variables
├── outputs.tf         # Output values
├── provider.tf        # AWS provider config
├── terraform.tfvars   # Variable values
└── README.md          # Project documentation
```
---

## ⚙️ Prerequisites

Terraform v1.3+
AWS CLI configured with IAM credentials
An AWS account (Free Tier eligible)

---
## 📚 Resources


---
## 🔐 Security & Cost


All resources are created within AWS Free Tier limits.

Always run terraform destroy to avoid unintended charges.



---
## 👨‍💻 Author

Girish Potdar
[GitHub](https://github.com/girishpotdar) | [LinkedIn](https://www.linkedin.com/in/girish-potdar-525569140/)
