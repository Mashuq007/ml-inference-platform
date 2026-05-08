# ML Inference Platform on AWS

A production-style REST API serving an ML model,
deployed on AWS with a full CI/CD pipeline.

## Architecture
- EC2 (t2.micro) inside custom VPC
- Dockerized Flask API pulled from Amazon ECR
- Automated deploys via GitHub Actions on every push
- Model artifacts stored in S3
- Request logs in DynamoDB
- Monitoring via CloudWatch alarms

## Tech Stack
AWS (VPC · EC2 · ECR · S3 · DynamoDB · CloudWatch · IAM)
Docker · Python · Flask · scikit-learn · GitHub Actions

## Status
🔨 Phase 1 in progress — VPC + EC2 + IAM
