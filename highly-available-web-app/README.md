
# Highly Available Web Application on AWS

## Overview
This project demonstrates the design and deployment of a highly available web application architecture on AWS. The goal was to build a fault-tolerant and scalable system using core AWS services.

## Architecture
The architecture uses multiple Availability Zones to ensure high availability and resilience.

(Architecture diagram included in this folder)

## AWS Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group
- Amazon VPC
- IAM
- Amazon CloudWatch

## Design Decisions
- Deployed EC2 instances across multiple Availability Zones to eliminate single points of failure.
- Used an Application Load Balancer to distribute traffic across instances.
- Configured Auto Scaling to automatically adjust capacity based on demand.
- Used IAM roles instead of static credentials to follow security best practices.
- Restricted traffic using security groups.

## Monitoring and Reliability
- Used Amazon CloudWatch to monitor instance health and system performance.
- Enabled health checks to automatically replace unhealthy instances.

## What I Learned
- High availability design using Availability Zones
- IAM least-privilege access
- Monitoring and scaling cloud workloads

## Notes
Hands-on experience gained through AWS Cloud Quest and a personal AWS account.
