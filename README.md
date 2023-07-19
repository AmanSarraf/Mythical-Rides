# Wild Rydes Sample Project

![Wild Rydes Logo](wildrydes-logo.png)

Wild Rydes is a serverless web application built on AWS, showcasing how to create scalable and reliable applications using various AWS services. The project allows users to request mythical creatures (unicorns) for a ride, sign up, and sign in to the application. The application is designed to demonstrate best practices for building modern web applications on the AWS platform.

## Technologies Used

- Frontend: HTML, CSS, JavaScript (React/Angular/Vue.js)
- Backend: AWS Lambda, Amazon API Gateway
- Authentication: Amazon Cognito
- Database: Amazon DynamoDB
- Storage: Amazon S3
- Hosting: Amazon S3
- Security and Authorization: AWS IAM
- Monitoring and Logging: Amazon CloudWatch

## Getting Started

Follow the steps below to set up and deploy the Wild Rydes application on your AWS account.

### Prerequisites

1. [AWS Account](https://aws.amazon.com/free/) - Create a free AWS account if you don't have one already.
2. AWS CLI - Install and configure the AWS Command Line Interface on your development machine.

### Deployment

1. **Frontend**:

   - Clone the repository to your local machine.
   - Navigate to the `frontend` directory.
   - Set up your frontend application using your preferred JavaScript framework (React/Angular/Vue.js).
   - Update the necessary configuration files (e.g., API endpoint URLs) to match your AWS setup.

2. **Backend**:

   - Navigate to the `backend` directory.
   - Create AWS Lambda functions for different functionalities (e.g., ride requests, user authentication).
   - Use Amazon API Gateway to define RESTful API endpoints and link them to the corresponding Lambda functions.
   - Set up Amazon Cognito for user authentication and authorization.

3. **Database**:

   - Create an Amazon DynamoDB table to store user and ride data.
   - Define the necessary table schema and access patterns.

4. **Storage and Hosting**:

   - Create an Amazon S3 bucket to store static frontend assets (HTML, CSS, JavaScript).
   - Upload frontend files to the S3 bucket for static content hosting.
   - Store unicorn images in another S3 bucket.

5. **Security and Authorization**:

   - Configure AWS IAM roles and policies to control access to AWS resources.
   - Implement proper authentication and authorization using Amazon Cognito and IAM.

6. **Monitoring and Logging**:

   - Set up Amazon CloudWatch to collect logs and metrics from AWS Lambda, API Gateway, and other relevant services.
   - Create alarms for critical events or performance issues.

### Usage

Once the application is deployed, users can access it using the provided URL. They can sign up, sign in, and request a ride using the frontend interface. Unicorn images are
