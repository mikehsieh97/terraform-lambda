# Terraform + AWS Lambda example

Using Terraform to manage AWS Lambda functions


# Steps

```
cd repo
terraform init
python3 -m venv venv
source venv/bin/activate
pip install boto3
pip freeze > requirements.txt

terraform plan


./deploy.sh
```