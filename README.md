# Terraform AWS VPC - Production Grade Infrastructure

Automated a complete production-grade AWS VPC using Terraform (Infrastructure as Code).

## Architecture
- Custom VPC (10.0.0.0/16)
- 2 Public Subnets + 2 Private Subnets across 2 AZs
- Internet Gateway + NAT Gateway
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG) with Nginx
- Bastion Host
- Security Groups

## Tools Used
- Terraform v1.15.5
- AWS (ap-south-1 Mumbai region)
- Ubuntu

## How to Run
```bash
terraform init
terraform plan
terraform apply
terraform destroy
```

## Author
Sonal Solanki - Cloud & DevOps Engineer - Bangalore
