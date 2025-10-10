# AWSProjects
Building 5 Resume Projects with AWS services for 5 weeks
List of Projects Building 

🗓️ Week 1 — Foundation: Serverless & Data Flow Basics 

Theme: Learn core AWS services + serverless architecture 
 Goal: Build your first end-to-end serverless data pipeline 

 

🎯 Learning Focus 

AWS CLI & IAM fundamentals (permissions, roles, least privilege) 

AWS Lambda basics (triggers, event handling) 

S3 as storage and data lake 

Glue, Athena, and QuickSight for ETL and visualization 

 

🧩 Mini Projects (Days 1–3) 

IAM & S3 Hands-on: 

Create IAM roles & policies for Lambda & S3. 

Upload sample CSVs to S3 and access them programmatically. 

Lambda Basics: 

Write a simple Python Lambda that processes JSON data and saves to S3. 

Athena + QuickSight: 

Query CSVs in S3 via Athena. 

Visualize results in QuickSight dashboard. 

 

🏗️ Resume Project (Days 4–7) 

Project: Serverless Marketing Analytics Pipeline 
 Description: 
 Automate campaign data ingestion, transform it using Glue, query insights with Athena, and visualize in QuickSight. 

Key AWS Services: 
 S3, Lambda, Glue, Athena, QuickSight, SNS, IAM 

Deliverables: 

Architecture diagram 

Code in GitHub 

README.md with STAR format 

Metrics: “Reduced manual reporting from 4h → 10m” 

Resume Line: 

Designed a serverless data analytics pipeline (S3, Lambda, Glue, Athena, QuickSight) to automate marketing reporting, reducing manual reporting time by 95%. 

 

🗓️ Week 2 — Compute & Networking: Scalable Web Architecture 

Theme: Learn EC2, Load Balancing, RDS, and cost-effective scaling 
 Goal: Deploy a full web app with high availability 

 

🎯 Learning Focus 

EC2, Security Groups, and key pairs 

Load Balancing (ALB) + Auto Scaling groups 

RDS setup and connection 

CloudWatch basics for monitoring 

 

🧩 Mini Projects (Days 1–3) 

Launch EC2 → install Apache/Nginx → serve a webpage. 

Create RDS MySQL instance → connect via EC2 app. 

Configure ALB + Auto Scaling group → test scale-up/down triggers. 

 

🏗️ Resume Project (Days 4–7) 

Project: Scalable E-Commerce Application on AWS 
 Description: 
 Deploy a dynamic shopping web app on EC2 behind ALB with RDS Multi-AZ backend and CloudFront caching. 

Key AWS Services: 
 EC2, ALB, Auto Scaling, RDS, CloudFront, Route 53, IAM 

Deliverables: 

Architecture diagram with multi-AZ design 

Auto Scaling demo (screenshots / metrics) 

README.md + STAR summary 

Resume Line: 

Architected a scalable e-commerce web application using EC2 Auto Scaling, RDS Multi-AZ, and ALB, achieving 99.9% uptime and 3x performance under peak load. 

 

🗓️ Week 3 — Networking & Security: Building a Secure VPC 

Theme: Dive deep into AWS network isolation and compliance 
 Goal: Create a secure, multi-tier architecture with private/public subnets 

 

🎯 Learning Focus 

VPC, Subnets, Route Tables, NACLs, and Security Groups 

Bastion Host setup and SSH tunneling 

NAT Gateway & private subnet isolation 

CloudTrail and GuardDuty monitoring 

 

🧩 Mini Projects (Days 1–3) 

Create a custom VPC with 2 public + 2 private subnets. 

Deploy a Bastion Host → SSH into private EC2. 

Enable GuardDuty → simulate suspicious activity alerts. 

 

🏗️ Resume Project (Days 4–7) 

Project: Secure Multi-Tier VPC with Bastion and Monitoring 
 Description: 
 Design a compliant AWS network with isolated subnets, monitored traffic, and least-privilege IAM policies. 

Key AWS Services: 
 VPC, EC2, NAT, Bastion, IAM, CloudTrail, GuardDuty, CloudWatch 

Deliverables: 

Network diagram (public/private tiers) 

Demo log insights from CloudTrail 

STAR-style README.md 

Resume Line: 

Implemented a secure multi-tier VPC with private subnets, Bastion host, and GuardDuty monitoring, reducing attack surface and ensuring compliance-ready design. 

 

🗓️ Week 4 — Serverless + AI: Intelligent Automation 

Theme: Combine serverless design with AI/ML services 
 Goal: Build a smart chatbot using AWS AI services 

 

🎯 Learning Focus 

Amazon Lex for conversational interfaces 

AWS Lambda integration 

DynamoDB for persistence 

Comprehend for NLP sentiment analysis 

 

🧩 Mini Projects (Days 1–3) 

Build a Lex bot with 3 intents and test responses. 

Integrate Lex → Lambda → DynamoDB for dynamic replies. 

Add Comprehend to analyze customer sentiment. 

 

🏗️ Resume Project (Days 4–7) 

Project: AI-Powered Customer Support Chatbot 
 Description: 
 Develop an intelligent chatbot using Lex and Lambda that understands customer queries and tracks sentiment with Comprehend. 

Key AWS Services: 
 Lex, Lambda, DynamoDB, Comprehend, CloudWatch 

Deliverables: 

Chat flow diagram 

Working demo (Lex test console or web UI) 

README.md + metrics (“Handled 60% of support queries automatically”) 

Resume Line: 

Developed a serverless AI chatbot using Amazon Lex, Lambda, and Comprehend, automating 60% of customer queries and reducing response time to 10s. 

 

🗓️ Week 5 — Cost Optimization & Observability 

Theme: Learn cloud economics and monitoring automation 
 Goal: Create a real-time AWS cost and performance dashboard 

 

🎯 Learning Focus 

AWS Cost Explorer API 

CloudWatch custom metrics & dashboards 

DynamoDB for data aggregation 

QuickSight for visualization 

 

🧩 Mini Projects (Days 1–3) 

Query AWS Billing & Cost Explorer manually. 

Automate cost data collection with Lambda + DynamoDB. 

Build a CloudWatch dashboard showing service costs. 

 

🏗️ Resume Project (Days 4–7) 

Project: Real-Time AWS Cost Optimization Dashboard 
 Description: 
 Create a serverless system that retrieves, stores, and visualizes daily AWS spend, identifying unused resources automatically. 

Key AWS Services: 
 Lambda, Cost Explorer API, DynamoDB, QuickSight, CloudWatch 

Deliverables: 

Visualization dashboard 

Lambda scheduler code 

README.md with cost-saving insights 

Resume Line: 

Built a real-time AWS cost dashboard (Lambda, DynamoDB, QuickSight) to track daily spend and identify idle resources, reducing monthly costs by 20%. 

 

