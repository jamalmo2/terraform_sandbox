# Terraform AWS VPC Provisioning

This Terraform code provisions a simple AWS VPC with public and private subnets, an internet gateway, route tables, and a security group.

## Prerequisites
- Terraform installed on your local machine. You can download it [here](https://www.terraform.io/downloads.html).
- AWS account with appropriate permissions.

## Usage
1. Clone this repository to your local machine.
2. Navigate to the directory containing the Terraform code.
3. Run `terraform init` to initialize the Terraform environment.
4. Run `terraform plan` to see the execution plan.
5. Run `terraform apply` to apply the changes and provision the infrastructure.
6. After provisioning, run `terraform destroy` to tear down the infrastructure.

## Best Practices
- Use variables to parameterize your Terraform code for reusability and maintainability.
- Use modules to encapsulate and reuse common infrastructure patterns.
- Follow the principle of least privilege when defining IAM roles and permissions.
- Enable version control for your Terraform code using Git and maintain descriptive commit messages.
- Use Terraform state management to track the state of your infrastructure and manage it effectively.

