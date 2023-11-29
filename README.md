# serverless
> ✅ Active status <br>

## About
| Name          | NUID        |
| ---           | ---         |
| Navin Sharma  | 002737702   |

## Index
  - [Introduction](#objective)
  - [User Requirements 📝](#user-requirements)
  - [Prerequisites](#prerequisites)

## Objective
The objective of this is to develop a serverless application that simplifies and automates the process of creating Lambda functions in AWS. This application provides a user-friendly interface for defining Lambda functions, including their code, configuration, and triggers. It also handles the deployment of Lambda functions to AWS and automate the management of their lifecycle.

## User Requirements
1. Create Submission API
2. Implement Lambda Function
3. The Lambda function will be invoked by the SNS notification.
4. The Lambda function is responsible for following:
5. Download the release from the GitHub repository and store it in Google Cloud Storage Bucket.
6. Email the user the status of download.
7. Track the emails sent in DynamoDB.

## Prerequisites
- AWS Account with IAM User Access
- GitHub Account
- Google Cloud Account with Storage Access
- NodeJs Development Environment
- Basic understanding of AWS Lambda, SNS, DynamoDB, GitHub, Google Cloud Storage