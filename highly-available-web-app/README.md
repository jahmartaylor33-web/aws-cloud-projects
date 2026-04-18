

# Highly Available Web Application on AWS

## Overview
This project demonstrates the design and deployment of a highly available and
scalable web application architecture on AWS. The objective was to build a
fault-tolerant system using core AWS services and best practices.

## Architecture
The application is deployed across multiple Availability Zones to eliminate
single points of failure and improve resiliency.



## Architecture
The application is deployed across multiple Availability Zones to eliminate
single points of failure and improve resiliency.

### Architecture Diagram
![Multi-AZ EC2 Architecture](diagrams/highly-available-web-app-architecture.png)





### Supporting Screenshots

#### EC2 Compute and Instance Management
![EC2 Instance Management](screenshots/ec2-instances.png)


## AWS Services Used
- Amazon EC2
- Application Load Balancer (ALB)
- Auto Scaling Group
- Amazon VPC
- AWS Identity and Access Management (IAM)
- Amazon CloudWatch

## Design Decisions
- Deployed EC2 instances across multiple Availability Zones for fault tolerance
- Used an Application Load Balancer to distribute incoming traffic
- Configured Auto Scaling to adjust capacity automatically based on demand
- Used IAM roles instead of static credentials to follow security best practices
- Restricted network access using security groups

## Monitoring and Reliability
- Used Amazon CloudWatch to monitor instance health and performance
- Enabled health checks to automatically replace unhealthy instances

## What I Learned
- High availability design using Availability Zones
- IAM least‑privilege access
- Monitoring and scaling AWS workloads

## Notes
This project was completed through hands-on learning with AWS Cloud Quest and a
personal AWS account.

