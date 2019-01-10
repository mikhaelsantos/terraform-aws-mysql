# Terraform configuration to deploy an AWS EC2 instance with MYSQL
## Description
This projects contains the module necessary to deploy an AWS EC2 instance with auto-scaling and roles, profiles and ports for MYSQL.
It also contains as an starting points:
- **policy-json** : To define the policies the instance might need.
- **assume-role-policy** : To be able to assume toles
- **mysql-init-config**: The basic to get a mysql instance installed and running
- **tfvars file**: with configurable values to set for the instance e.g: Instance Size, Desired Count, Image Id, etc

## Requirements
* Terraform >= 0.11.10
* Terraform provider.aws >= v1.54.0
* Usage of terraform workspaces
* AWS account and credentials configured with necessary priviliges
* AWS CLI >= 1.14.59



