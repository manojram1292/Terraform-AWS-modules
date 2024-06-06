# S3 Module

## Description
This module creates an S3 bucket.

## Usage

```hcl
module "s3" {
  source = "./s3"

  bucket_name = "my-bucket"
}
