# `AWS S3 Bucket Terraform Project`

This project automates the deployment of a static website to an Amazon S3 bucket using Terraform. The website files are uploaded to the S3 bucket, and the bucket is configured for static website hosting with public access.

## Prerequisites

- [Terraform](https://www.terraform.io/downloads.html) installed on your local machine
- AWS account with appropriate permissions to create S3 buckets

## Usage

1. **Clone the repository:**

    ```sh
    git clone https://github.com/ShubhamMca88/aws-s3-bucket-terraform-project.git

    cd aws-s3-bucket-terraform-project
    ```

2. **Initialize Terraform:**

    ```sh
    terraform init
    ```

3. **Plan the Terraform deployment:**

    ```sh
    terraform plan
    ```

4. **Apply the Terraform configuration:**

    ```sh
    terraform apply
    ```

5. **Upload your static website:**

    After the S3 bucket is created, you can upload your static website files to the bucket.


## Cleanup

To destroy the resources created by Terraform, run:

```sh
terraform destroy
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

