# 🏗️ Terraform AWS Free Tier Lab

A hands-on lab using **Terraform** to provision AWS infrastructure within the **Free Tier** limits. This project is designed to demonstrate basic infrastructure-as-code (IaC) skills, reusable modules, and deployment automation practices.

------------------------
🚀 Features
------------------------

- ✅ Create VPC, Subnets, Internet Gateway, Route Tables
- ✅ Provision EC2 instance (Amazon Linux 2)
- ✅ Attach Security Groups and Key Pairs
- ✅ Create an S3 bucket
- ✅ Use remote state with Terraform backend (optional)
- ✅ Written with Free Tier limits in mind

------------------------
📁 Project Structure
------------------------

```bash
terraform-aws-free-tier-lab/
│
├── main.tf            # Core resources
├── variables.tf       # Input variables
├── outputs.tf         # Output values
├── provider.tf        # AWS provider config
├── terraform.tfvars   # Variable values
└── README.md          # Project documentation

------------------------
⚙️ Prerequisites
------------------------
Terraform v1.3+
AWS CLI configured with IAM credentials
An AWS account (Free Tier eligible)


------------------------
🔧 Setup & Usage
------------------------

# 1. Clone the repo
git clone https://github.com/girishpotdar/terraform-aws-free-tier-lab.git
cd terraform-aws-free-tier-lab

# 2. Initialize Terraform
terraform init

# 3. Review the execution plan
terraform plan

# 4. Apply the infrastructure changes
terraform apply

# 5. Destroy resources when done
terraform destroy


------------------------
🔐 Security & Cost
------------------------

All resources are created within AWS Free Tier limits.

Always run terraform destroy to avoid unintended charges.

------------------------
📦 Optional Improvements
------------------------

Add remote backend with S3 + DynamoDB
Add EC2 provisioning via user data or Ansible
Add module-based folder structure for better reusability

------------------------
👨‍💻 Author
------------------------
Girish Potdar
GitHub | LinkedIn
