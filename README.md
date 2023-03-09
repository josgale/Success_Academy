# Success_Academy

The following Terraform components will create/deploy services to AWS Lambda, IAM, S3, SES and Route 53.

- Please check 'tfvars.json' to update variables

1. Navigate to 'infrastructure/02_services'
2. Run 'terraform init' from the command line
3. Run 'terraform plan -var-file=tfvars.json' to see the changes Terraform will make to the infrastructure
4. Run 'terraform apply -var-file=tfvars.json' to deploy the changes to your infrastructure
5. Run 'terraform destroy -var-file=tfvars.json' to remove the changes to your infrastructure
