# InfraAutomation
Examples for how to do various infrastructure and configuration automation.

## Getting Started

Note: These examples assume various foundational pieces have been configured such as authentication in the case of the AWS and some basic infrastructure set up in the case of VSphere.

### Terraform Resources
Follow the official [install guide](https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/aws-get-started).

Useful commands:
- `terraform plan` -> preview changes
- `terraform apply` -> Deploy changes

### CDK Resources
Follow the official [getting started guide](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html).

Useful commands:
- `cdk synth` -> Validate and Build CFN stack 
- `cdk deploy` -> Deploy default app
