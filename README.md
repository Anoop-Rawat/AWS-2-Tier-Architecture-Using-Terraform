# AWS-2-Tier-Architecture-Using-Terraform
Scenario:
Deploy a two-tier architecture for your company. For the foundational project you are allowed to have all your code in a single main.tf file (known as a monolith) with hardcoded data.

1. Deploy a VPC with CIDR 10.0.0.0/16 with 2 public subnets with CIDR 10.0.1.0/24 and 10.0.2.0/24. 
Each public subnet should be in a different AZ for high availability.

2. Create 2 private subnet with CIDR ‘10.0.3.0/24’ and ‘10.0.4.0/24’ with an RDS MySQL instance (micro) in one of the subnets. Each private subnet should be in a different AZ.

3. A load balancer that will direct traffic to the public subnets.

4. Deploy 1 EC2 t2.micro instance in each public subnet.

Prerequisites:

Install Terraform CLI
Install AWS CLI
GitHub account
The main.tf & variables.tf files from our GitHub repo
AWS account access
https://registry.terraform.io/

Reference : https://medium.com/all-things-devops/terraform-deploy-a-two-tier-architecture-e686e20e9708
