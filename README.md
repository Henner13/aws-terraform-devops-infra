# AWS Terraform DevOps Infraestructure

## Overview
This proyect provisions a basic but production-oriented AWS infraestructure using Terraform.

## Architecture
- VPC with public and private subnets
- EC2 instances
- Security groups
- IAM roles


## Tech Stack
- AWS
- Terraform
- Linux


## How to Deploy
```
terraform init
```

```
terraform plan
```

```
terraform apply
```

## Security Considerations
- IAM roles instead of access keys
- Restricted security groups
- No secrets in code

