# Terraform Practice

This repository is a personal playground for learning and experimenting with [Terraform](https://www.terraform.io/) — an Infrastructure as Code (IaC) tool used to automate and manage cloud resources.

## ⚠️ Disclaimer

This repository was created as a self-directed learning project to explore Terraform and AWS infrastructure on my own time. It is intended purely for experimentation and may contain incomplete, rough, or in-progress configurations. While the code may not always reflect production-ready standards, the goal is to deepen my understanding through hands-on practice.


## Purpose

To gain hands-on experience with:
- Spinning up AWS EC2 instances
- Defining infrastructure using HCL (`.tf` files)
- Managing lifecycle of cloud resources with `terraform apply` and `terraform destroy`
- Learning DevOps fundamentals from a practical perspective

## Tools & Technologies

- **Terraform**
- **AWS EC2**
- **Amazon Linux 2 AMI**
- (Optional) **AWS CLI**

## Getting Started

> These steps will guide you through your first deployment.

### Prerequisites
- AWS account with access keys
- Terraform installed (`terraform -v`)
- (Optional) AWS CLI installed

## Steps

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Terraform-Practice.git
   cd Terraform-Practice

2. Create a file named main.tf and paste your configuration.

3. Initialize Terraform:

   ```bash
   terraform init

4. Preview the plan:

   ```bash
   terraform plan

5. Apply to create resources:

   ```bash
   terraform apply

6. Destroy resources when done:

   ```bash
   terraform destroy

## Folder Structure

```bash
   Terraform-Practice/
   ├── main.tf          # Main Terraform configuration
   └── README.md        # This file
```

## Resources

[**Terraform Docs:**](https://developer.hashicorp.com/terraform/docs)

[**AWS EC2 Documentation:**](https://docs.aws.amazon.com/ec2/)

[**Terraform AWS Provider:**](https://registry.terraform.io/providers/hashicorp/aws/latest)
