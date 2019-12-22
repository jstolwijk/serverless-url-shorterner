# serverless-url-shorterner

## Create bucket via command line:

`aws s3api create-bucket --bucket tf-serverless-jesse --region eu-west-1 --create-bucket-configuration LocationConstraint=eu-west-1`

Upload to bucket:
`aws s3 cp src.zip s3://tf-serverless-jesse/v1.0.0/src.zip`

## Terraform

Init: `terraform init`

Apply changes: `terraform apply`

https://medium.com/dazn-tech/deploying-aws-api-gateway-with-iam-auth-using-openapi-3-0-and-terraform-27fda7e7cf2a

https://learn.hashicorp.com/terraform/aws/lambda-api-gateway
