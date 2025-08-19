# 📊 Serverless Visitor Analytics Web App

A serverless web application that tracks visitors with real-time counter functionality using AWS S3, CloudFront, Lambda, DynamoDB, IAM roles, and JavaScript for client-side API integration.

## 🏗️ Architecture

- **Frontend**: Static website hosted on Amazon S3
- **CDN**: CloudFront for global content delivery
- **Backend**: AWS Lambda functions
- **Database**: DynamoDB for visitor counter storage
- **Security**: IAM roles for API access

## ✨ Features

- Interactive greeting interface
- Persistent visitor counter with real-time tracking
- Global content delivery
- High availability and fault tolerance
- Zero maintenance

## 📋 Setup

1. Create DynamoDB table for visitor counter
2. Deploy Lambda functions with DynamoDB integration
3. Upload static files to S3 bucket
4. Configure CloudFront distribution
5. Set up IAM roles and API access
6. Integrate client-side JavaScript with REST endpoints

## 🏆 Benefits

- Serverless design with automatic scaling
- Pay-per-use cost model
- High availability across AWS regions
- Fault tolerant architecture
- Zero server maintenance required
