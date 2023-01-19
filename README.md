## Learn Terraform Cloudflare Static Website

Learn how to use Terraform to set up a static website using AWS bucket for object storage and Cloudflare for DNS, SSL and CDN. Follow along with [this tutorial](https://learn.hashicorp.com/tutorials/terraform/cloudflare-static-website) on HashiCorp Learn.

The [`acm-cloudfront`](https://github.com/hashicorp/learn-terraform-cloudflare-static-website/tree/acm-cloudfront) branch uses ACM for SSL certificate and Cloudfront for CDN. This configuration is more complex and works even if your S3 bucket name is already taken.

This tutorial ends here, however I will be adding to the complexity to teach myself other aspects of terraform. 

I will create a lambda function to password protect the S3 bucket in AWS console. 

I will then import that function and required settings into terraform so it can be managed via IAS. 