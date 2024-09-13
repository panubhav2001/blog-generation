# Blog Generation with AWS Bedrock and Lambda

This project is an AWS Lambda function that generates a blog based on a provided topic using the Bedrock LLM (LLaMA-3) and saves the generated blog content to an S3 bucket.

## Features

- Generates a blog of 200 words based on a given topic using **AWS Bedrock** with the LLaMA-3 model.
- Saves the generated blog content to an S3 bucket.
- Configurable parameters such as generation length, temperature, and top-p.

## Prerequisites

- **AWS Account** 
- **Boto3** Python SDK installed for interaction with AWS services.
- **AWS Lambda** with a properly configured IAM role for Bedrock and S3 access.

## Setup

### 1. Install Required Libraries
Ensure you have `boto3` and `botocore` installed:

```bash
pip install boto3 botocore
