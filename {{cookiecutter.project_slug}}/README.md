# Terraform module: {{ cookiecutter.module_name }}
*{{ cookiecutter.description }}*

## Pre-requisite
  - [terraform](https://www.terraform.io/downloads.html) 1.7+

## Usage
- Initialize Terraform:
  ```bash
  terraform init
  ```
- To bootstrap the whole infrastructure:
  ```bash
  terraform plan
  terraform apply
  ```

## License
This code is developed by {{ cookiecutter.author }}.
