# EC2 Module

## Description
This module creates an EC2 instance.

## Usage

```hcl
module "ec2" {
  source = "./ec2"

  ami           = "ami-0c55b159cbfafe1f0"
  instance_type = "t2.micro"
  instance_name = "my-instance"
}
