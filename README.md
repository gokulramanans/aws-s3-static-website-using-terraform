# aws-s3-static-website-using-terraform
This repository contains Terraform code to provision an AWS S3 bucket that hosts a static website. The infrastructure is automated using Terraform
![image](https://github.com/user-attachments/assets/70301fca-21bd-460b-b738-8bbad37abf33)

Overview
This project deploys a static website using an S3 bucket and configures it with the following features:

Static Website Hosting: S3 bucket configured to serve index.html and error.html as the default documents.
Logging Bucket: A separate, private S3 bucket is created to store logs of the website's activity.
Public Access Block: Public access is allowed for the static website while maintaining privacy for the logging bucket.
Bucket Policy: A policy is applied to allow public access to the files in the website bucket.
Versioning: Optionally enables versioning for the static website bucket to track and manage file versions.
Ownership Controls: Ensures the proper configuration of object ownership and supports public ACLs.
Features
S3 Bucket for Static Website: Hosts the static website's HTML files, including the default index and error pages.
Logging Configuration: Configures logging to track access to the static website.
Public Access Settings: Configures the static website bucket to be publicly accessible, while the logging bucket is kept private.
Versioning: Optionally enables S3 versioning for better management of the files.
Ownership Controls: Ensures correct ownership and access permissions.
