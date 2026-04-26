# Terraform Learning Configs

Personal reference repo built while learning Terraform. Each folder is a standalone mini-project covering a specific concept or AWS service.

## What's Inside

| Folder | What I Learned |
|--------|----------------|
| `tf-variables` | Variables, locals, tfvars |
| `tf-functions` | Built-in Terraform functions |
| `tf-data-sources` | Fetching existing resources |
| `tf-operators-exps` | Expressions and conditionals |
| `tf-backend` | Remote state with S3 + DynamoDB |
| `tf-cli-workspace` | Workspaces for environments |
| `tf-module-vpc` | Using public registry modules |
| `tf-own-module-VPC` | Writing custom modules |
| `tf-multi-resources` | Provisioning multiple resources |
| `tf-test` | Terraform testing framework |
| `testing-local-module` | Testing local modules |
| `aws-vpc` | VPC, subnets, route tables |
| `aws-ec2` | EC2 + security groups |
| `aws-vpc-ec2-nginx` | VPC + EC2 + Nginx |
| `aws-s3` | S3 buckets and policies |
| `aws-IAM-management` | IAM users, roles, policies |
| `proj-static-website` | Static site on S3 + CloudFront |

## Usage

```bash
cd <folder-name>
terraform init
terraform plan
terraform apply
```

> ⚠️ Remember to `terraform destroy` after testing to avoid AWS charges.
