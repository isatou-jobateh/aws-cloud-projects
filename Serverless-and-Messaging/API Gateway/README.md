# Amazon API Gateway and AWS Lambda – FAQ Microservice

## Overview

This project was completed as part of an AWS Skill Builder hands-on lab. The goal was to create a simple FAQ microservice using Amazon API Gateway and AWS Lambda.

The service accepts an HTTP GET request and returns a JSON object containing a random question-and-answer pair.

## AWS Services Used

* **Amazon API Gateway:** Receives HTTP requests and provides an endpoint for the microservice.
* **AWS Lambda:** Executes the function code that processes the request and generates a response.
* **Amazon CloudWatch:** Helps monitor and troubleshoot API Gateway and Lambda execution.
* **AWS Identity and Access Management (IAM):** Manages permissions required by AWS services.

## How It Works

1. A user sends an HTTP GET request to the API Gateway endpoint.
2. API Gateway receives the request and forwards it to the Lambda function.
3. Lambda processes the request and generates a JSON response containing a question-and-answer pair.
4. The response returns through API Gateway.
5. API Gateway sends the HTTP response to the user.
6. CloudWatch helps with monitoring and troubleshooting.

## Key Concepts Learned

* API endpoints and HTTP GET requests
* Integrating API Gateway with Lambda
* Serverless microservices
* JSON requests and responses
* Monitoring and troubleshooting with CloudWatch
* IAM permissions

## What I Learned

I learned how API Gateway acts as the entry point for an application and how it connects HTTP requests to a Lambda function. I also learned how the two services can work together to build a simple serverless microservice without managing servers.

## Project Status

**Completed** — AWS Skill Builder hands-on lab.

The lab's knowledge check was passed, and the microservice was successfully created in the lab environment.
