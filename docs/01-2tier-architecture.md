# High Availability 2-Tier Architecture on AWS

## Overview
Designed a fault-tolerant and scalable web application using Multi-AZ AWS infrastructure to ensure high uptime.

## Architecture Diagram
![AWS 2-Tier Architecture](./assets/Architecture_Diagram.png)

## Responsibilities
- Designed VPC network with public/private subnets across 2 Availability Zones
- Launched EC2 Auto Scaling Group using Launch Template
- Implemented Application Load Balancer for traffic distribution
- Deployed RDS MySQL with Multi-AZ backup and automated snapshots
- Configured Security Groups & IAM roles for least-privilege access
- Implemented CloudWatch alarms for ASG scaling policies

## Outcome
- Achieved 99.9% service uptime with auto-healing
- Improved performance & reduced risk of single-point failure
