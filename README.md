# terraform-module-validate

A GitHub Actions reusable workflow that runs the following steps to validate the Terraform module:

- checkout source code
- install tools
- terraform fmt
- terraform init
- terraform validate
- tflint
- tfsec
