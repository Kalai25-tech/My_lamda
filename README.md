Objective
Develop a serverless AWS solution that automatically scans all AWS Regions for Security
Groups with unrestricted inbound access (0.0.0.0/0), stores the scan results in Amazon
S3, and sends an email notification using Amazon SNS.
The solution is completely automated using Amazon EventBridge Scheduler and AWS
Lambda