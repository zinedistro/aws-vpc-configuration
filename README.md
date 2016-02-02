# AWS Initial VPC and Security Group Configuration

Initial AWS Virtual Private Cloud and security group configuration using Terraform from the examples [here](https://github.com/hashicorp/atlas-examples/blob/master/setup/vpc.md) codified into a repository.


# Setup:

Create a `terraform.tfvars` file in the root of the repository with the following keys:

```sh
AWS_ACCESS_KEY_ID="Your AWS Key ID"
AWS_SECRET_ACCESS_KEY="Your AWS secret access key"
AWS_DEFAULT_REGION="us-east-1"
name="Default Network"
source_cidr_block="10.0.0.0"
availability_zone="us-east-1a"
```
