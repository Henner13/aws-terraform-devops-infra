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
```bash
terraform init
```

```bash
terraform plan
```

```bash
terraform apply
```

## Security Considerations
- IAM roles instead of access keys
- Restricted security groups
- No secrets in code

---
---
# AWS Terraform DevOps Infraestructure (Infraestructura DevOps con AWS y Terraform)

## Descripción General
Este proyecto aprovisiona una infraestructura básica de AWS orientada a producción utilizando Terraform.

## Arquitectura
- VPC con subredes públicas y privadas
- Instancias EC2
- Grupos de seguridad (Security Groups)
- Roles de IAM


## Stack Tecnológico
- AWS
- Terraform
- Linux


## Cómo Desplegar
```bash
terraform init
```
```bash
terraform plan
```

```bash
terraform apply
```

## Consideraciones de Seguridad
- Uso de roles IAM en lugar de claves de acceso
- Grupos de seguridad con acceso restringido
- Sin secretos ni credenciales de código
