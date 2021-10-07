# terraform_repo_testing

This is just a test

## Usage

```
module "my_ec2_instance" {
  source                  = "https://github.com/JeremyYonathanC/terraform_test"
  ec2_instance_ami_id     = <Your instance ami id>
  ec2_instance_type       = "t3.micro"
  ec2_instance_name       = "sample"
}

```
