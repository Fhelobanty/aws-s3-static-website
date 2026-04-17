# 🌐 Static Website Hosting on AWS S3

## Project Overview
This project demonstrates how to deploy a fully functional static website using Amazon S3. The goal was to understand cloud storage, access control, and how to make content publicly accessible over the internet without using a traditional web server.

## Architecture
User → Browser → Internet → AWS S3 → Static Website
<img width="1000" height="700" alt="aws_s3_static_website_architecture (1)" src="https://github.com/user-attachments/assets/948ee834-2410-47da-89c5-905257b3fef3" />


## Implementation Steps

### 1. Created S3 Bucket
- Configured a globally unique bucket name
- Selected appropriate AWS region

### 2. Configured Public Access
- Disabled "Block all public access"
- Applied a bucket policy to allow public read access

### 3. Enabled Static Website Hosting
- Configured `index.html` as the entry point

### 4. Uploaded Website Files
- HTML and CSS files uploaded to S3 bucket

### 5. Tested Deployment
- Accessed the website using the S3 endpoint URL

## Live Demo
http://my-portfolio-website224.s3-website-ap-southeast-2.amazonaws.com/

## Screenshots
Web Testing; <img width="1920" height="996" alt="Done s3 web" src="https://github.com/user-attachments/assets/18e9b96a-a1f7-46ec-ba2c-bee2c78350c6" />
Files in S3; <img width="1920" height="460" alt="Done Object" src="https://github.com/user-attachments/assets/409b7793-65ee-4f0f-ba3f-28c8b4c901de" />

## Key Skills Demonstrated
- Amazon S3 (Object Storage)
- Static Website Hosting
- IAM & Bucket Policies
- Basic Web Hosting Concepts
- Cloud Deployment Workflow

## Outcome

Successfully deployed a publicly accessible static website using AWS S3 without a traditional web server.

## Author

Atoyebi Micheal.
Aspiring Cloud Engineer
