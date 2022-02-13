# CS4843 Assignment 1: Host static website using AWS S3 buckets and CloudFront
### Created by Miguel Fabrigas
### Website URL: https://d3oyhfi94nsgv6.cloudfront.net

## About
This is a simple static website to test out the static website hosting capabilites of AWS using S3 buckets and CloudFront. There are 5 pages: a main page with links to every other page, an About Me page, a Resume page, an "art gallery" page, and an error page when a user accesses the website incorrectly.

## AWS Setup
1. Create an S3 bucket on AWS with a globally unique name.
2. Enable this S3 bucket for public access and static website hosting, setting the main page and error page.
3. Upload all associated static website files to this S3 bucket.
4. Create a CloudFront distribution.
5. Set this CloudFront distribution's origin domain to the S3 bucket created earlier.
6. Enable OAI for this CloudFront distribution and update the S3 bucket's policy to allow OAI access.
7. Set the CloudFront distribution's default root object to the website's main page.
8. Deploy the CloudFront distribution.
