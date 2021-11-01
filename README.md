# ami-infrastructure
Author: Yongji Shen
Date: 2021/10/03


Manually Create a user account - `ghactions_ami` in dev account and attach the policies for AMI CI/CD workflow

Steps:
1. Create a `terraform.tfvars` which contains 2 variables
    <ol>
    <li>account_profile = "dev"</li>
    <li>region = "us-east-1"</li>
    </ol>
2. terraform apply