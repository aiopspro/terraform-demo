# Terraform-Demo
## Create a S3 Bucket
## Configure Keys and Secrets
aws configure
Access key ID : 
Secret access key: 
region : eu-west-1
format : json

##Note: Once AWS config done, perform below command
1) navigate to “.tf” files. Open “resource_s3.tf” and update the “bucket” argument.
terraform init
terraform validate
terraform plan -out "s3.tfplan"
terraform apply "s3.tfplan"
terraform destroy
