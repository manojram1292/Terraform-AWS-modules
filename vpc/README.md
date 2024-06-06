# VPC Module

## Description
This module creates a Virtual Private Cloud (VPC) along with subnets, route tables, and internet gateways.

## Usage

```hcl
module "vpc" {
  source = "./vpc"

  vpc_name   = "my-vpc"
  cidr_block = "10.0.0.0/16"
}
