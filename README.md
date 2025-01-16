# Cloud_Architecture_Design
## Project Overview
This repository contains the cloud architecture design for ABC, a fictional e-commerce company. The solution focuses on migrating ABC's infrastructure to AWS to enhance scalability, availability, and analytics capabilities while ensuring secure handling of sensitive customer data.

## Key Components
Web Server: Deployed using EC2 instances with Auto Scaling for high availability.
Database: Amazon RDS with MySQL for structured data storage.
Caching: ElastiCache (Redis) for faster data retrieval and improved performance.
Load Balancing: Elastic Load Balancers to distribute traffic efficiently.
Analytics: Amazon Redshift and AWS Lambda for data warehousing and real-time analytics.
Redundancy: Multi-region replication using VPCs and Route 53 for failover.
Email Service: Integrated email service for targeted customer communication.
