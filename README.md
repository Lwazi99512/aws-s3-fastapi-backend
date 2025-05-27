# aws-s3-fastapi-backend# aws-s3-fastapi-backend
# 🧠 Bedrock RAG Chatbot – AWS & FastAPI

A secure, scalable AI chatbot powered by AWS Bedrock and FastAPI. Designed to demonstrate AWS cloud services, IAM security, and application deployment.

## 🔧 Tech Stack
- FastAPI (Python)
- AWS Bedrock (RAG-based model integration)
- AWS S3 (for file storage)
- IAM Roles + `.env` for secure credentials

## 🚀 Features
- FastAPI backend with `/chat` endpoint
- Secure .env configuration with boto3
- Ready for integration with a React frontend
- S3 Bucket created for file storage
- Future goals: deploy on EC2, add user auth with Cognito

## 🛡️ Security Considerations
- Uses least-privilege IAM policies
- Environment variables instead of hardcoding credentials
- Scoped access to S3 buckets

## 📁 Project Structure

