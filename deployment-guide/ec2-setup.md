# EC2 Setup Guide

## Instance Details
- Region: us-east-1 (N. Virginia)
- Instance Type: t3.micro
- Platform: Linux / UNIX
- Availability Zone: us-east-1f

## Steps Followed
1. Logged into AWS Console
2. Opened EC2 service
3. Launched new instance
4. Selected Ubuntu AMI
5. Created key pair
6. Configured security group
7. Launched instance

## SSH Command
```bash
ssh -i mykey.pem ubuntu@<public-ip>
