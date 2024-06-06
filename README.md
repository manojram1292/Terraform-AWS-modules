# Terraform AWS Modules

## Description
This repository contains reusable Terraform modules for provisioning various AWS resources. Each module is designed to be flexible and easy to integrate into your Terraform projects.

## Modules
- [VPC](./vpc)
- [EC2](./ec2)
- [S3](./s3)
- [RDS](./rds)

## Usage
Each module has its own README with usage instructions. Below is a general example of how to use a module.

### Example Usage

```hcl
module "vpc" {
  source = "./vpc"

  vpc_name   = "my-vpc"
  cidr_block = "10.0.0.0/16"
}
