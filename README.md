# AWS_S3_Cloudfront_Static_Website
This project demonstrates how to host a static website using AWS S3 and distribute it using Amazon CloudFront for faster content delivery.

#Before starting, ensure you have:
-An AWS Free Tier account
-Basic knowledge of AWS services

# create a s3 bucket in AWS 

1.Log in to the AWS Console.
2.Go to S3 and click Create Bucket.
3.Enter a unique Bucket Name (e.g., my-static-site).
4.Select a region (e.g., us-east-1).
6.Uncheck "Block all public access" to allow public file access.
7.Click Create Bucket.

# Enable Static Website Hosting
1.Open your S3 bucket and go to the Properties tab.
2.Scroll to Static website hosting and click Edit.
3.Select Enable and set the Index document to index.html.
4.Click Save Changes.
