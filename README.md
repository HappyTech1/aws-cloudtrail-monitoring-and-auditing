# AWS CloudTrail Monitoring and Auditing

## Overview

This project demonstrates the creation and configuration of AWS CloudTrail for monitoring, auditing, and logging AWS account activity. CloudTrail records API calls, user actions, and account events across AWS services, helping organizations improve security visibility, compliance, and incident investigations.

## Objectives

* Create and configure AWS CloudTrail.
* Enable logging of management and data events.
* Store logs securely in Amazon S3.
* Monitor user activities and API calls.
* Review CloudTrail event history.
* Support security auditing and compliance requirements.

## Technologies Used

* AWS CloudTrail
* Amazon S3
* AWS IAM
* AWS Management Console

## Project Steps

### 1. Sign in to AWS Console

Log in to the AWS Management Console using an account with administrative permissions.

### 2. Create an S3 Bucket

1. Navigate to **Amazon S3**.
2. Click **Create Bucket**.
3. Enter a unique bucket name.
4. Select the desired AWS Region.
5. Create the bucket.

### 3. Create a CloudTrail Trail

1. Navigate to **CloudTrail**.
2. Select **Trails**.
3. Click **Create Trail**.
4. Enter a trail name.
5. Choose the S3 bucket created earlier.
6. Enable logging for all regions.
7. Create the trail.

### 4. Generate AWS Activity

Perform actions such as:

* Creating IAM users
* Launching EC2 instances
* Viewing AWS resources
* Updating security settings

These actions generate CloudTrail events.

### 5. Review Event History

1. Open CloudTrail.
2. Select **Event History**.
3. Filter events by:

   * Username
   * Event Source
   * Resource Name
   * Event Type

### 6. Analyze Logs

Review recorded events including:

* Console logins
* IAM changes
* EC2 actions
* S3 access events
* Security-related activities

## Benefits of CloudTrail

* Security Monitoring
* Incident Investigation
* Compliance Reporting
* User Activity Tracking
* Change Management
* Audit Readiness

## Screenshots

Add screenshots of:

* CloudTrail Dashboard
* Trail Creation
* S3 Bucket Configuration
* Event History Logs
* Recorded AWS Activities

Example:

```text
screenshots/
├── cloudtrail-dashboard.png
├── create-trail.png
├── s3-log-bucket.png
├── event-history.png
└── cloudtrail-events.png
```

## Key Learning Outcomes

* Understanding AWS auditing services.
* Monitoring account activity using CloudTrail.
* Investigating AWS events and API calls.
* Managing log storage in Amazon S3.
* Supporting security and compliance requirements.

## Author

Obinna

GitHub: https://github.com/HappyTech1
