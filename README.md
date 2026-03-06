# ecommerce-cloud-project
# E-commerce Cloud Architecture Project

## Objective
Create a cloud account and design architecture for a scalable e-commerce platform.

## Cloud Provider
Amazon Web Services (AWS)

## Steps Completed
1. Created AWS cloud account
2. Explored AWS dashboard and services
3. Documented free tier limitations
4. Designed e-commerce architecture
5. Created project structure and version control
6. Documented setup steps

## AWS Services Used
- EC2 (Compute server)
- S3 (Storage for product images)
- RDS (Database for orders and users)
- CloudFront (Content delivery network)
- IAM (Security and access management)

## Architecture Overview

Users access the e-commerce website through the internet. Requests go through CloudFront CDN and Load Balancer, which routes traffic to EC2 servers. Product data is stored in RDS, while images are stored in S3.

