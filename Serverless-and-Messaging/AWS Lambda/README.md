# AWS Lambda – S3 Event-Driven Function

## Overview

AWS Lambda is a serverless compute service that allows code to run without managing servers.

In this lab, I created an AWS Lambda function and configured an Amazon S3 bucket as an event source. I then triggered the Lambda function by uploading an object to the S3 bucket and monitored the function execution using Amazon CloudWatch Logs.

## AWS Services

* AWS Lambda
* Amazon S3
* Amazon CloudWatch
* AWS IAM

## Lab Objectives

The objectives of this lab were to:

* Create an AWS Lambda function
* Configure an Amazon S3 bucket as a Lambda event source
* Trigger a Lambda function by uploading an object to Amazon S3
* Monitor Lambda function activity through Amazon CloudWatch Logs

## How It Works

The lab demonstrated an event-driven architecture:

```text
Amazon S3
    │
    │ Object uploaded
    ▼
AWS Lambda
    │
    │ Function executes
    ▼
Amazon CloudWatch Logs
```

When an object was uploaded to the configured S3 bucket, the S3 event triggered the Lambda function.

The Lambda execution was then recorded in CloudWatch Logs, allowing the function activity to be monitored.

## Lab Tasks

### 1. Create a Lambda Function

Created an AWS Lambda function and configured its basic settings.

### 2. Configure Amazon S3 as an Event Source

Configured an S3 bucket to trigger the Lambda function when an object was uploaded.

### 3. Trigger the Lambda Function

Uploaded an object to the S3 bucket, which generated an event and caused the Lambda function to execute.

### 4. Monitor Lambda Execution

Used Amazon CloudWatch Logs to view information about the Lambda function execution.

## Key Concepts Learned

* AWS Lambda
* Serverless computing
* Lambda functions
* Lambda event sources
* Amazon S3 event notifications
* Event-driven architecture
* Lambda execution
* Amazon CloudWatch Logs
* IAM permissions

## What I Learned

This lab gave me hands-on experience with event-driven serverless computing.

I learned how an S3 event can automatically trigger a Lambda function without requiring a continuously running server. I also learned how CloudWatch Logs can be used to monitor Lambda function executions and troubleshoot function activity.

## Evidence

Screenshots from the completed AWS Skill Builder lab are included in this project folder.

Suggested structure:

```text
AWS Lambda/
├── README.md
└── Lambda~Lab~Screenshots/
    ├── 01-lab~objectives.png
    ├── 02-lambda-function.png
    ├── 03-s3-event-source.png
    ├── 04-lambda-trigger.png
    └── 05-cloudwatch-logs.png
```

## Project Status

**Completed — Hands-on AWS Skill Builder Lab**

This project was completed using an AWS Skill Builder lab environment. The resources used during the exercise were created for the lab and were cleaned up after completion.
