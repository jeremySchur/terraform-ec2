# Terraform AWS EC2 Instance

This repository contains Terraform configuration files to create an AWS EC2 instance with a security group.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed on your local machine
- AWS account with appropriate permissions
- AWS CLI configured with your credentials

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/jeremySchur/terraform-ec2.git
    cd learn-terraform-aws-instance
    ```

2. Initialize the Terraform configuration:
    ```sh
    terraform init
    ```

3. Review the plan:
    ```sh
    terraform plan
    ```

4. Apply the configuration:
    ```sh
    terraform apply
    ```

5. Confirm the apply action with `yes`.

## Configuration

The main configuration file is `main.tf`, which includes the following resources:
- `aws_instance`: Defines the EC2 instance.
- `aws_security_group`: Defines the security group for the instance.

## Cleanup

To destroy the created resources, run:
```sh
terraform destroy
```
Confirm the destroy action with `yes`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- Jeremy Schur - [jeremySchur](https://github.com/jeremySchur)

## Acknowledgments

- [Terraform Documentation](https://www.terraform.io/docs)
- [AWS Documentation](https://docs.aws.amazon.com/)
