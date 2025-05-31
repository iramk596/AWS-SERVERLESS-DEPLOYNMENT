# AWS-SERVERLESS-DEPLOYNMENT

This project demonstrates a serverless web app built using:

Amazon S3 – for static website hosting

API Gateway – for creating RESTful APIs

AWS Lambda – for backend logic

DynamoDB – for data storage

CloudFront – for secure, fast content delivery

🚀 Features
Static frontend hosted on S3

Serverless backend with API Gateway + Lambda

NoSQL database using DynamoDB

CloudFront for HTTPS and CDN performance

Fully managed, scalable, and cost-efficient setup

🗂️ Project Structure
bash
Copy
Edit
.
├── frontend/    # HTML, CSS, JS
├── backend/     # Lambda functions
└── README.md
✅ How It Works
User accesses the site via CloudFront

Frontend loads from S3

API calls go through API Gateway

Logic runs in Lambda

Data is stored in DynamoDB

📦 Deployment (Manual)
Upload frontend to S3 and enable static hosting

Deploy Lambda functions and connect to API Gateway

Set up DynamoDB tables

Configure CloudFront for S3 and API Gateway with HTTPS
