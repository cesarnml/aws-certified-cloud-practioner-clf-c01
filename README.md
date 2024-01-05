# AWS Certified Cloud Practioner Course - CLF-C02

- [AWS Certified Cloud Practioner Course - CLF-C02](#aws-certified-cloud-practioner-course---clf-c02)
  - [Lesson Plan (30 hours)](#lesson-plan-30-hours)
  - [Lesson Notes](#lesson-notes)
    - [1. Introduction](#1-introduction)
    - [2. What is Cloud Computing](#2-what-is-cloud-computing)
    - [3. IAM - Identity and Access Management](#3-iam---identity-and-access-management)
    - [4. EC2 - Elastic Compute Cloud](#4-ec2---elastic-compute-cloud)
    - [5. EC2 Instance Storage](#5-ec2-instance-storage)
    - [6. ELB \& ASG - Elastic Load Balancing \& Auto Scaling Groups](#6-elb--asg---elastic-load-balancing--auto-scaling-groups)
    - [7. Amazon S3 (Simple Storage Solution)](#7-amazon-s3-simple-storage-solution)
    - [8. Databases \& Analytics](#8-databases--analytics)
    - [9. Other Compute Services: ECS Lambda, Batch, Lightsail](#9-other-compute-services-ecs-lambda-batch-lightsail)
    - [10. Deployment \& Managing Infrastructure at Scale](#10-deployment--managing-infrastructure-at-scale)
    - [11. Leveraging the AWS Global Infrastructure](#11-leveraging-the-aws-global-infrastructure)
    - [12. Cloud Integrations](#12-cloud-integrations)
    - [13. Cloud Monitoring](#13-cloud-monitoring)
    - [14. VPC \& Networking](#14-vpc--networking)

## Lesson Plan (30 hours)

- [x] ~~_*1. Introduction (12min)*_~~ [2024-01-01]
  - [x] ~~_*Lesson 001 - Course Introduction*_~~ [2024-01-01]
  - [x] ~~_*Lesson 002 - Creating an AWS Account*_~~ [2024-01-01]
  - [x] ~~_*Lesson 003 - Important Message*_~~ [2024-01-01]
  - [x] ~~_*Lesson 004 - About your instructor*_~~ [2024-01-01]
- [x] ~~_2. What is Cloud Computing (33min)_~~ [2024-01-01]
  - [x] ~~_*Lesson 005 - Traditional IT Overview*_~~ [2024-01-01]
  - [x] ~~_*Lesson 006 - What is Cloud Computing*_~~ [2024-01-01]
  - [x] ~~_*Lesson 007 - The Different Types of Cloud Computing*_~~ [2024-01-01]
  - [x] ~~_Lesson 008 - AWS Cloud Overview_~~ [2024-01-01]
  - [x] ~~_Lesson 009 - Tour of the Console & Services in AWS_~~ [2024-01-01]
  - [x] ~~_Lesson 010 - About the UI changes in the course_~~ [2024-01-01]
  - [x] ~~_Lesson 011 - Shared Responsibility Model & AWS Acceptable Policy_~~ [2024-01-01]
- [x] ~~_3. IAM - Identity and Access Management (57min)_~~ [2024-01-03]
  - [x] ~~_Lesson 012 - IAM Introduction: Users, Groups, Policies_~~ [2024-01-01]
  - [x] ~~_Lesson 013 - IAM Users & Groups Hands On_~~ [2024-01-01]
  - [x] ~~_Lesson 014 - IAM Policies_~~ [2024-01-01]
  - [x] ~~_Lesson 015 - IAM Policies Hands On_~~ [2024-01-01]
  - [x] ~~_Lesson 016 - IAM MFA Overview_~~ [2024-01-03]
  - [x] ~~_Lesson 017 - IAM MFA Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 018 - AWS Access Keys, CLI and SDK_~~ [2024-01-03]
  - [x] ~~_Lesson 019 - AWS CLI Setup on Windows_~~ [2024-01-03]
  - [x] ~~_Lesson 020 - AWS CLI Setup on Mac_~~ [2024-01-03]
  - [x] ~~_Lesson 021 - AWS CLI Setup on Linux_~~ [2024-01-03]
  - [x] ~~_Lesson 022 - AWS CLI Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 023 - AWS CloudShell_~~ [2024-01-03]
  - [x] ~~_Lesson 024 - IAM Roles for AWS Services_~~ [2024-01-03]
  - [x] ~~_Lesson 025 - IAM Roles Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 026 - IAM Security Tools_~~ [2024-01-03]
  - [x] ~~_Lesson 027 - IAM Security Tools Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 028 - IAM Best Practices_~~ [2024-01-03]
  - [x] ~~_Lesson 029 - Shared Responsibility Model for IAM_~~ [2024-01-03]
  - [x] ~~_Lesson 030 - IAM Summary_~~ [2024-01-03]
- [x] ~~_4. EC2 - Elastic Compute Cloud (85min)_~~ [2024-01-03]
  - [x] ~~_Lesson 031 - AWS Budget Setup_~~ [2024-01-03]
  - [x] ~~_Lesson 032 - EC2 Basics_~~ [2024-01-03]
  - [x] ~~_Lesson 033 - Create an EC2 Instance with EC2 User Data to have a Website Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 034 - EC2 Instance Types Basics_~~ [2024-01-03]
  - [x] ~~_Lesson 035 - Security Groups & Classic Ports Overview_~~ [2024-01-03]
  - [x] ~~_Lesson 036 - Security Groups Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 037 - SSH Overview_~~ [2024-01-03]
  - [x] ~~_Lesson 038 - How to SSH using Linus or Mac_~~ [2024-01-03]
  - [x] ~~_Lesson 039 - How to SSH using Windows_~~ [2024-01-03]
  - [x] ~~_Lesson 040 - How to SSH usingWindows 10_~~ [2024-01-03]
  - [x] ~~_Lesson 041 - EC2 Instance Connect_~~ [2024-01-03]w
  - [x] ~~_Lesson 042 - EC2 Instance Roles Demo_~~ [2024-01-03]
  - [x] ~~_Lesson 043 - EC2 Instance Purchasing Options_~~ [2024-01-03]
  - [x] ~~_Lesson 044 - Shared Responsibility Model for EC2_~~ [2024-01-03]
  - [x] ~~_Lesson 045 - EC2 Summary_~~ [2024-01-03]
- [x] ~~_*5. EC2 Instance Storage (43min)*_~~ [2024-01-04]
  - [x] ~~_Lesson 046 - EBS Overview_~~ [2024-01-03]
  - [x] ~~_Lesson 047 - EBS Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 048 - EBS Snapshots Overview_~~ [2024-01-03]
  - [x] ~~_Lesson 049 - EBS Snapshots Hands On_~~ [2024-01-03]
  - [x] ~~_Lesson 050 - AMI Overview_~~ [2024-01-03]
  - [x] ~~_Lesson 051 - AMI Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 052 - EC2 Image Builder Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 053 - EC2 Instance Store_~~ [2024-01-04]
  - [x] ~~_Lesson 054 - EFS Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 055 Shared Responsibility Model for EC2 Storage_~~ [2024-01-04]
  - [x] ~~_Lesson 056 - Amazon FSx Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 057 - EC2 Instance Storage Summary_~~ [2024-01-04]
  - [x] ~~_Lesson 058 - Section Cleanup_~~ [2024-01-04]
- [x] ~~_6. ELB & ASG - Elastic Load Balancing & Auto Scaling Groups (39min)_~~ [2024-01-04]
  - [x] ~~_Lesson 059 - High Availability, Scalability, Elasticity_~~ [2024-01-04]
  - [x] ~~_Lesson 060 - Elastic Load Balancing (ELB) Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 061 - Application Load Balancer (ALB) Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 062 - Auto Scaling Groups (ASG) Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 063 - Auto Scaling Groups (ASG) Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 064 - Auto Scaling Groups (ASG) Strategies_~~ [2024-01-04]
  - [x] ~~_Lesson 065 - Section Cleanup_~~ [2024-01-04]
  - [x] ~~_Lesson 066 - ELB & ASG Summary_~~ [2024-01-04]
- [x] ~~_7. Amazon S3 (67min)_~~ [2024-01-04]
  - [x] ~~_Lesson 067 - S3 Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 068 - S3 Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 069 - S3 Security: Bucket Policy_~~ [2024-01-04]
  - [x] ~~_Lesson 070 - S3 Security: Bucket Policy Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 071 - S3 Website Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 072 - S3 Website Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 073 - S3 Versioning Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 074 - S3 Versioning Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 075 - S3 Replication Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 076 - S3 Replication Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 077 - S3 Storage Classes Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 078 - S3 Storage Classes Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 079 - S3 Encryption_~~ [2024-01-04]
  - [x] ~~_Lesson 080 - Shared Responsibility Model for S3_~~ [2024-01-04]
  - [x] ~~_Lesson 081 - AWS Snow Family Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 082 - AWS Snow Family Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 083 - Storage Gateway Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 084 - S3 Summary_~~ [2024-01-04]
- [x] ~~_8. Databases & Analytics (48min)_~~ [2024-01-04]
  - [x] ~~_Lesson 085 - Databases Introduction_~~ [2024-01-04]
  - [x] ~~_Lesson 086 - RDS & Aurora Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 087 - RDS Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 088 - RDS Deployments Options_~~ [2024-01-04]
  - [x] ~~_Lesson 089 - ElastiCache Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 090 - DynamoDB Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 091 - DynamoDB Hands On_~~ [2024-01-04]
  - [x] ~~_Lesson 092 - DynamoDB Global Tables_~~ [2024-01-04]
  - [x] ~~_Lesson 093 - Redshift Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 094 - EMR Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 095 - Athena Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 096 - QuickSight Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 097 - DocumentDB Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 098 - Neptune Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 099 - QLDB Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 100 - Managed Blockchain Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 101 - Glue Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 102 - DMS Overview_~~ [2024-01-04]
  - [x] ~~_Lesson 103 - Databases & Analytics Summary_~~ [2024-01-04]
- [x] ~~_9. Other Compute Services: ECS, Lambda, Batch, Lightsail (39min)_~~ [2024-01-05]
  - [x] ~~_Lesson 104 - What is Docker?_~~ [2024-01-05]
  - [x] ~~_Lesson 105 - ECS, Fargate & ECR Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 106 - Serverless Introduction_~~ [2024-01-05]
  - [x] ~~_Lesson 107 - Lambda Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 108 - Lambda Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 109 - API Gateway Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 110 - Batch Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 111 - Lightsail Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 112 - Lightsail Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 113 - Other Compute - Summary_~~ [2024-01-05]
- [x] ~~_10. Deployment & Managing Infrastructure at Scale (62min)_~~ [2024-01-05]
  - [x] ~~_Lesson 114 - CloudFormation Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 115 - CloudFormation Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 116 - CDK Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 117 - Beanstalk Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 118 - Beanstalk Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 119 - CodeDeploy Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 120 - CodeCommit Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 121 - CodeBuild Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 122 - CodePipeline Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 123 - CodeArtifact Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 124 - CodeStar Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 125 - Cloud9 Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 126 - CodeStar & Cloud9 Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 127 - Systems Manager (SSM) Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 128 - SSM Session Manager_~~ [2024-01-05]
  - [x] ~~_Lesson 129 - OpsWorks Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 130 - Deployment Summary_~~ [2024-01-05]
- [x] ~~_11. Leveraging the AWS Global Infrastructure (48min)_~~ [2024-01-05]
  - [x] ~~_Lesson 131 - Why Global Applications?_~~ [2024-01-05]
  - [x] ~~_Lesson 132 - Route 53 Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 133 - Route 53 Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 134 - CloudFront Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 135 - CloudFront Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 136 - S3 Transfer Acceleration_~~ [2024-01-05]
  - [x] ~~_Lesson 137 - AWS Global Accelerator_~~ [2024-01-05]
  - [x] ~~_Lesson 138 - AWS Outposts_~~ [2024-01-05]
  - [x] ~~_Lesson 139 - AWS WaveLength_~~ [2024-01-05]
  - [x] ~~_Lesson 140 - AWS Local Zones_~~ [2024-01-05]
  - [x] ~~_Lesson 141 - Global Applications Architecture_~~ [2024-01-05]
  - [x] ~~_Lesson 142 - Leveraging the AWS Global Infrastructure Summary_~~ [2024-01-05]
- [x] ~~_12. Cloud Integrations (18min)_~~ [2024-01-05]
  - [x] ~~_Lesson 143 - Cloud Integrations Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 144 - SQS Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 145 - SQS Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 146 - Kinesis Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 147 - SNS Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 148 - SNS Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 149 - Amazon MQ Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 150 - Cloud Integrations Summary_~~ [2024-01-05]
- [x] ~~_13. Cloud Monitoring (40min)_~~ [2024-01-05]
  - [x] ~~_Lesson 151 - CloudWatch Metrics & CloudWatch Alarms Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 152 - CloudWatch Metrics & CloudWatch Alarms Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 153 - CloudWatch Logs Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 154 - CloudWatch Logs Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 155 - EventBridge Overview (formerly CloudWatch Events)_~~ [2024-01-05]
  - [x] ~~_Lesson 156 - EventBridge Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 157 - CloudTrail Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 158 - CloudTrail Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 159 - X-Ray Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 160 - CodeGuru Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 161 - AWS Health Dashboard_~~ [2024-01-05]
  - [x] ~~_Lesson 162 - AWS Health Dashboard - Hands On_~~ [2024-01-05]
  - [x] ~~_Lesson 163 - Cloud Monitoring Summary_~~ [2024-01-05]
- [ ] 14. VPC & Networking (33min)
  - [x] ~~_Lesson 164 - VPC Overview_~~ [2024-01-05]
  - [x] ~~_Lesson 165 - IP Addresses in AWS_~~ [2024-01-05]
  - [x] ~~_Lesson 166 - VPC, Subnet, Internet Gateway & NAT Gateways_~~ [2024-01-05]
  - [x] ~~_Lesson 167 - Security Groups & Network Access Control List (NACL)_~~ [2024-01-05]
  - [ ] Lesson 168 - VPC Flow Logs & VPC Peering
  - [ ] Lesson 169 - VPC Endpoints - Interface & Gateway (s3 & DynamoDB)
  - [ ] Lesson 170 - PrivateLink
  - [ ] Lesson 171 - Direct Connect & Site-to-Site VPN
  - [ ] Lesson 172 - Client VPN
  - [ ] Lesson 173 - Transit Gateway Overview
  - [ ] Lesson 174 - VPC & Networking Summary
- [ ] 15. Security & Compliance (54min)
  - [ ] Lesson 175 - Shared Responsibility Model: Reminders & Examples
  - [ ] Lesson 176 - DDoS Protection: WAF & Shield
  - [ ] Lesson 177 - AWS Network Firewall
  - [ ] Lesson 178 - Penetration Testing
  - [ ] Lesson 179 - Encryption with KMS & CloudHSM
  - [ ] Lesson 180 - Encryption with KMS & CloudHSM Hands On
  - [ ] Lesson 181 - AWS Certificate Manager (ACM) Overview
  - [ ] Lesson 182 - Secrets Manager Overview
  - [ ] Lesson 183 - Artifact Overview
  - [ ] Lesson 184 - GuardDuty Overview
  - [ ] Lesson 185 - Inspector Overview
  - [ ] Lesson 186 - Config Overview
  - [ ] Lesson 187 - Macie Overview
  - [ ] Lesson 188 - Security Hub Overview
  - [ ] Lesson 189 - Amazon Detective Overview
  - [ ] Lesson 190 - AWS Abuse
  - [ ] Lesson 191 - Root User Privileges
  - [ ] Lesson 192 - IAM Access Analyzer
  - [ ] Lesson 193 - Security & Compliance Summary
- [ ] 16. Machine Learning (20min)
  - [ ] Lesson 194 - Rekognition Overview
  - [ ] Lesson 195 - Transcribe Overview
  - [ ] Lesson 196 - Polly Overview
  - [ ] Lesson 197 - Translate Overview
  - [ ] Lesson 198 - Lex + Connect Overview
  - [ ] Lesson 199 - Comprehend Overview
  - [ ] Lesson 200 - SageMaker Overview
  - [ ] Lesson 201 - Forecast Overview
  - [ ] Lesson 202 - Kendra Overview
  - [ ] Lesson 203 - Personalize Overview
  - [ ] Lesson 204 - Textract Overview
  - [ ] Lesson 205 - Machine Learning Summary
- [ ] 17. Account Management, Billing & Support (78min)
  - [ ] Lesson 206 - Organizations Overview
  - [ ] Lesson 207 - Organizations Hands On
  - [ ] Lesson 208 - Organizations Consolidated Billing
  - [ ] Lesson 209 - AWS Control Tower Overview
  - [ ] Lesson 210 - AWS Control Tower Hands On
  - [ ] Lesson 211 - AWS Resource Access Manager (AWS RAM)
  - [ ] Lesson 212 - AWS Service Catalog - Overview
  - [ ] Lesson 213 - Pricing Models of the Cloud
  - [ ] Lesson 214 - Savings Plan Overview
  - [ ] Lesson 215 - Compute Optimizer Overview
  - [ ] Lesson 216 - Billing & Costing Tools Overview
  - [ ] Lesson 217 - Estimating Costs in the Cloud - Pricing Calculator
  - [ ] Lesson 218 - Tracking Costs in the Cloud - Billing Dashboard, Cost Allocation Tags, Reports
  - [ ] Lesson 219 - Monitoring Costs in the Cloud - Billing Alarms & AWS Budgets
  - [ ] Lesson 220 - AWS Cost Anomaly Detection
  - [ ] Lesson 221 - AWS Service Quotas
  - [ ] Lesson 222 - AWS Trusted Advisor
  - [ ] Lesson 223 - Support Plans for AWS
  - [ ] Lesson 224 - Account Best Practices Summary
  - [ ] Lesson 225 - Billing Summary
- [ ] 18. Advanced Identity (9min)
  - [ ] Lesson 226 - Security Token Service (STS) Overview
  - [ ] Lesson 227 - Cognito Overview
  - [ ] Lesson 228 - Directory Services Overview
  - [ ] Lesson 229 - AWS IAM Identity Center
  - [ ] Lesson 230 - Advanced Identity - Summary
- [ ] 19. Other Services (29min)
  - [ ] Lesson 231 - Other Services - Section Intro
  - [ ] Lesson 232 - WorkSpaces Overview
  - [ ] Lesson 233 - AppStream 2.0 Overview
  - [ ] Lesson 234 - IoT Core Overview
  - [ ] Lesson 235 - Elastic Transcoder Overview
  - [ ] Lesson 236 - AppSync
  - [ ] Lesson 237 - Amplify
  - [ ] Lesson 238 - Device Farm Overview
  - [ ] Lesson 239 - AWS Backup Overview
  - [ ] Lesson 240 - Disaster Recovery Strategies
  - [ ] Lesson 241 - AWS Elastic Disaster Recover (DRS)
  - [ ] Lesson 242 - AWS DataSync
  - [ ] Lesson 243 - Application Discovery Service & Application Migration Service
  - [ ] Lesson 244 - AWS Migration Evaluator
  - [ ] Lesson 245 - AWS Fault Injection Simulator (FIS)
  - [ ] Lesson 246 - Step Functions
  - [ ] Lesson 247 - Ground Station
  - [ ] Lesson 248 - AWS Pinpoint
- [ ] 20. AWS Architecting & Ecosystem (52min)
  - [ ] Lesson 249 - AWS WhitePapers Well-Architected Framework
  - [ ] Lesson 250 - Pillar 1: Operational Excellence
  - [ ] Lesson 251 - Pillar 2: Security
  - [ ] Lesson 252 - Pillar 3: Reliability
  - [ ] Lesson 253 - Pillar 4: Performance Efficiency
  - [ ] Lesson 254 - Pillar 5: Cost Optimization
  - [ ] Lesson 255 - Pillar 6: Sustainability
  - [ ] Lesson 256 - AWS Well-Architected Tool
  - [ ] Lesson 257 - AWS Cloud Adoption Framework (CAF)
  - [ ] Lesson 258 - Right Sizing
  - [ ] Lesson 259 - AWS Ecosystem
  - [ ] Lesson 260 - AWS Knowledge Center
  - [ ] Lesson 261 - AWS IQ & re:Post
  - [ ] Lesson 262 - AWS Managed Services
- [ ] 21. Preparing for the Exam + Practice Exam - AWS CCP (23min)
  - [ ] Lesson 263 - Words on Other Services
  - [ ] Lesson 264 - State of Learning Checkpoint - AWS Certified Cloud Practioner
  - [ ] Lesson 265 - Exam Sample Question Walkthrough
  - [ ] Lesson 266 - Exam Tips - AWS Certified Cloud Practioner
  - [ ] Lesson 267 - Exam Walkthrough and Signup
  - [ ] Lesson 268 - Save 50% on your AWS Exam Cost
  - [ ] Lesson 269 - Get an Extra 30 Minutes on your AWS Exam - Non Native English Speakers only
- [ ] 22. Congratulations - AWS CCP (8min)
  - [ ] Lesson 270 - AWS Certification Paths
  - [ ] Lesson 271 - Congratulations - AWS Certified Cloud Practitioner
  - [ ] Lesson 272 - THANK YOU!

## Lesson Notes

### 1. Introduction

- AWS Cloud Practioner Exam - CLF-C02
- Will cover ~40 AWS services (out of 400+)
- Stephane Maarek (instructor)

### 2. What is Cloud Computing

- Client-Network-Model
- Server composed of:
  - 1. Compute
  - 2. Memory
  - 3. Storage
  - 4. Database
  - 5. Network
- Problems with traditional IT:
  - 1. High initial CAPEX
  - 2. Maintenance staff cost
  - 3. Ongoing upgrade/scaling monetary/time costs/constraints
- Cloud Computing:
  - 1. `on-demand delivery`
  - 2. `pay-as-you-go pricing`
  - 3. `provision exactly the right type and size of computing` that is needed
- 5 Characteristics of Cloud Computing
  - 1. `On-Demand Self Service`
  - 2. `Broad Network Access`
  - 3. `Multi-tenancy and Resource Pooling`
  - 4. `Rapid Elasticity and Scalability`
  - 5. `Measured Service`
- 6 Advantages of Cloud Computing
  - 1. Trade CAPEX for OPEX
  - 2. Benefit from massive economies of scale
  - 3. Stop guessing capacity
  - 4. Increase speed and agility
  - 5. Stop spending money on running and maintaining your own data centers
  - 6. Go global in minutes
- Problems solved by going Cloud
  - 1. Flexibility
  - 2. Cost-Effectiveness
  - 3. Scalability
  - 4. Elasticity
  - 5. High-availability and fault tolerance
  - 6. Agility
- History
  - 2002: AWS Internally launched
  - 2004: SQS first offering
  - 2006: Relaunched publicly with SQS, S3 & EC2
  - 2007: Europe release
- AWS Global Infrastructure
  - AWS Regions
    - Compliance, Proximity, Available Services, Pricing
  - AWS Availability Zones
    - Each regions has multiple AZ (3 - 6)
    - Each AZ is a discrete data center(s)
    - Isolated
    - Connected via high bandwidth, ultra-low latency networking
  - AWS Data Centers
  - AWS Edge Locations/Points of Presence
- AWS has `Global Services`
  - IAM, Route53, CloudFront, WAF
- AWS has `Region-scoped` services:
  - Amazon EC2, Elastic Beanstalk, Lambda, Rekognition
- Shared Responsibility Model
  - Customer responsible for the security `IN` the cloud
  - AWS responsible for the security `OF` the cloud
- AWS Acceptable Policy

### 3. IAM - Identity and Access Management

- `Root account` created by default, shouldn't be used or shared
- `Users` are people within your organization - can be
- `Groups` only contain users, not other groups
- Permissions assigned via JSON documents called `Policies`
  - `Least privilege principle`
- Policies can be attached to a group and the users of the group will all inherit the policy
- Or, policies can be `inlined` and only apply to a specific user
- IAM Policies Structure has 3 parts:
  - Version: "2012-10-17"
  - Id: identified for policy (optional)
  - Statement: one or more individual statements (required)
    - Sid: identified (optional)
    - Effect: `Allow` or `Deny`
    - Principal: `account`, `user` or `role` which policy applies to
    - Action: list of actions allowed or denied by policy
    - Resource: list of resources that policy applies to
- ARN: Amazon Resource Name
- MFA: Multi-Factor Authentication
  - MFA = password you **know** + security device you **own**
- Best practice to use MFA on Root Account and **all** IAM users
- MFA options:
  - Virtual MFA Device:
    - Google Authenticator
    - Authy
  - Universal 2nd Factor (U2F) Key (Security Key)
    - YubiKey
  - Hardware TOTP token
- 3 Ways to Access AWS:
  - AWS Management Console (protected by: password + MFA)
  - AWS CLI (protected by: access keys)
  - AWS SDK (protected by: access keys)
- Access Keys are generated via AWS Management Console
- `aws configure` - to setup aws cli with access key
- AWS CloudShell - browser-based terminal to interact with `aws-cli`
- IAM Roles (how we give permission to AWS Services)
  - EC2 Instance Roles
  - Lambda Function Roles
  - Roles for CloudFormation
- IAM Security Tools:
  - IAM Credentials Report (account-level)
  - IAM Access Advisor (user-level)
- Shared Responsibility Model
  - AWS: Infrastructure, Configuration, Compliance Validation
  - User (Me): Users, Groups, Policies, Management and Monitoring, Access Security
- IAM Summary:
  - ![](img/Screenshot%202024-01-03%20at%2010.12.03 AM.png)

### 4. EC2 - Elastic Compute Cloud

- Amazon EC2 - Infrastructure as a Service
  - Renting virtual machines (EC2 instances)
  - Storage (EBS or EFS)
  - Load balancers (ELB)
  - Scale services - Auto-scaling group (ASG)
- EC2 User Data (script):
  - bootstrap commands to initialize EC2 instance on initial boot
- EC2 instance types:
  - `t2.micro`
  - `t` - instance `class`
  - `2` - instance `generation`
  - `micro` - instance `size`
- Types:
  - General Purpose (t)
  - Compute Optimized (c)
  - Memory Optimized (r)
  - Storage Optimized (i,d,h1)
  - [EC2 Instance Type Comparison Site](https://instances.vantage.sh/)
- Security Groups - fundamental to `network security` in AWS
  - Control how traffic is allowed in and out of EC2 instances
  - Only contain `allow` rules
  - Can reference by IP or security group
  - By default: All in-bound traffic is BLOCKED; All out-bound traffic is ALLOWED
- Ports to Know:
  - ![](img/Screenshot%202024-01-03%20at%201.45.51 PM.png)
- SSH Login instructions:
  - Use `.pem` key and change permission to `chmod 0400 FILE.pem`
  - Run: `ssh -i FILE.pem ec2-user@PUBLIC_IP`
- EC2 Instance Connect - browser-based access to an EC2 Instance via AWS Management Console
- EC2 Instance Roles - authorize services for a given instance
- EC2 Instances Purchasing Options:
  - ![](./img/Screenshot%202024-01-03%20at%203.07.14 PM.png)
  - EC2 On Demand: billing per second, after first minute
  - EC2 Reserve Instances: Instance Type, Region, Tenancy, OS, Reservation Period (1-,3-years), Payment Options, Good for databases, Resell in Reserved Instance Marketplace - Convertible Reserved Instance for a bit more flexibility but less savings
  - EC2 Savings Plans - locked payment/hour then On-Demand, locked type
  - EC2 Spot Instances - MOST cost-efficient - good for batch jobs, image processing, data analysis, flexible start/end time, distributed workloads; not suitable for critical jobs/databases
- EC2 Summary:
  - ![](img/Screenshot%202024-01-03%20at%203.19.31 PM.png)

### 5. EC2 Instance Storage

- Elastic Block Store (EBS) Volume is a `network drive` that can be attached to an EC2 Instance - must be on same AZ
- EBS Snapshots - backup EBS Volumes
  - Useful in order to move an EBS volume to a different AZ
  - Recommended to detach EBS volume prior to generating snapshot
  - Features:
    - EBS Snapshot Archive - cheaper cost but delay in restore (1-3 days)
    - EBS Snapshot Recycle Bin - prevents accidental deletion of EBS Snapshots (1-day to 1-year)
- AMI - Amazon Machine Image - a \*_customization_ of an EC2 instance
  - There are **public** AMIs managed by AWS
  - Can create **custom** AMIs
  - Can launch **AWS Marketplace AMI**
- EC2 Image Builder - used to automate the creation of VMs or container images
  - Creation, Maintain and Validate EC2 AMIs
  - Can run on a schedule
- EC2 Instance Store - high-performance hardware disk (better than EBS - network)
  - ephemeral
  - Good for buffer / cache / scratch data - not good for long-term storage
  - Must be backup and replicate as needed by service
- EFS - Elastic File System (Managed NFS) can be mounted to 100s of EC2 instances
  - works only on Linux EC2 and in multi-AZ
  - EFS-IA (Elastic File System - Infrequent Access) - 92% lower cost
  - Storage class is cost-optimized for files not accessed frequently via Life Cycle Policy
- Amazon FSx
  - Launch 3rd party HPFS (High-Performance FileSystem)
    - For Lustre - High Performance Computing - Machine Learning/Analytics/Financial Modeling
    - For Windows File Server
    - For NetApp ONTAP
- EC2 Instance Storage Summary:
  - ![](img/Screenshot%202024-01-04%20at%207.16.50 AM.png)

### 6. ELB & ASG - Elastic Load Balancing & Auto Scaling Groups

- Vertical Scalability vs Horizontal Scalability
- High Availability running on at least 2 AZ
- Elastic Load Balancing (ELB) Overview
  - 4 Types of Load Balancers on AWS:
    - Application Load Balancer (HTTP/HTTPS) - Layer 7
    - Network Load Balancer (ultra-high performance, allows TCP) - Layer 4
    - Gateway Load Balancer - Layer 3
    - Classic Load Balancer (retired in 2023) - Layer 4 and Layer 7
  - It would be cheaper to setup your own LB, but more work on you
- Auto Scaling Group (ASG)
  - Add/Remove (scale out/in) EC2 instances as load increases/decreases
  - Manual Scaling
  - Dynamic Scaling
    - Simple/Step Scaling
    - Target Tracking Scaling
    - Scheduled Scaling
    - Predictive Scaling
- ELB & ASG Summary:
  - ![](./img/Screenshot%202024-01-04%20at%207.16.50 AM.png)

### 7. Amazon S3 (Simple Storage Solution)

- `Infinite Scaling` storage solution
- Used for:
  - backup and storage
  - disaster recovery
  - archive
  - hybrid cloud storage
  - application hosting
  - media hosting
  - data lakes & big data analytics
  - software delivery
  - static websites
- Amazon S3
  - store objects (files) in buckets (directories)
  - buckets must have a globally unique name
  - buckets are defined at the region level
  - names must have no uppercase, no underscore
  - 3-62 characters long
  - objects must have a `key`
  - object values are the content of the body (5 TB limit)
- Amazon S3 Security
  - User-Based:
    - IAM Policies that dictate which API calls should be allowed for a specific user
  - Resource-Based:
    - Bucket Policies - allows cross account access
    - Object Access Control List (ACL)
    - Bucket Access Control List (ACL)
  - Encryption
- Amazon S3 - Versioning
  - Enabled at the bucket level
  - Best practice to version buckets
- Amazon S3 - Replication
  - CRR - Cross Region Replication
  - SRR - Same Region Replication
  - Must enable Versioning in source and destination buckets
- S3 Storage Classes
  - Amazon S3 Standard
  - Amazon S3 Standard-Infrequent Access (IA)
  - Amazon S3 One Zone-Infrequent Access
  - Amazon S3 Glacier Instant Retrieval
  - Amazon S3 Glacier Flexible Retrieval
  - Amazon S3 Glacier Deep Retrieval
  - Amazon S3 Intelligent Tiering
- S3 Encryption
  - Server-Side Encryption (by default on) vs Client-Side Encryption
- AWS Snow Family
  - Offline devices to perform data migrations
  - AWS Snowball, Snowcone, Snowmobile
- AWS OpsHub (UI for Snow-family)
- Storage Gateway - bridge between on-premise data and cloud data in S3
- S3 Summary:
  - ![](./img/Screenshot%202024-01-04%20at%204.33.07 PM.png)

### 8. Databases & Analytics

- AWS RDS (Relational Database Service) Overview
  - Postgres
  - MySQL
  - MariaDB
  - Oracle
  - Microsoft SQL Server
  - Aurora DB (AWS Proprietary database)
    - PostgreSQL (3x) and MySQL (5x)
    - Grows at 10GB increment up to 128GB
- ![](img/Screenshot%202024-01-04%20at%207.48.28 PM.png)

### 9. Other Compute Services: ECS Lambda, Batch, Lightsail

- ![](img/Screenshot%202024-01-05%20at%209.32.00 AM.png)
- ![](img/Screenshot%202024-01-05%20at%209.32.56 AM.png)

### 10. Deployment & Managing Infrastructure at Scale

- ![](./img/Screenshot%202024-01-05%20at%2010.37.01 AM.png)
- ![](img/Screenshot%202024-01-05%20at%2010.37.54 AM.png)

### 11. Leveraging the AWS Global Infrastructure

- Route53 Managed DNS (Domain Name System)
  - Simple Policy - No health checks
  - Weighted Routing Policy - distribute traffic across multiple instances
  - Latency Routing Policy - performance enhancement via proximity
  - Failure Routing Policy - disaster recovery
- AWS Cloudfront
  - Content Delivery Network (CDN)
  - 216 Points of Presence
  - Great for hosting static content close to the user, has built-in cache optimizations
- S3 Transfer Acceleration
  - Increase upload/downloads to S3 by routing the transfer to an edge location instead of specific instance AZ
- AWS Global Accelerator
  - It's like you get on and off the AWS superhighway via edge locations instead of using the dirty internet of the masses that is bumping and slower.
  - [AWS Global Accelerator Speed Test](https://speedtest.globalaccelerator.aws)
- AWS Outposts
  - "Server Racks" same AWS infrastructure and you manage them the same way
  - An On-Premise version of AWS
- AWS Wavelength -> 5G Network (Deployment at the Edge - mobile speed at scale)
  - No additional charges
- AWS Local Zones
  - closer to end users to run latency-sensitive applications
- Global Applications Architecture
  - Single Region/AZ, Single Region, Multi AZ; Multi Region, Active-Passive; Multi Region Active-Active
- AWS Global Infrastructure Summary
  - ![](./img/Screenshot%202024-01-05%20at%2011.39.13 AM.png)
  - ![](./img/Screenshot%202024-01-05%20at%209.32.56 AM.png)

### 12. Cloud Integrations

- SQS (Simple Queue Service)
  - Producers - send messages into the SQS Queue
  - Consumers - pull messages from the SQS Queue
    - messages are created by Producers
    - messages are destroyed by Consumers after processing
  - 4 days default, 14 days max retention
  - FIFO Queue
    - First In First Out
- Kinesis
  - Real-time big data streaming
- Amazon SNS (pub/sub)
  - Simple Notification Service
    - SNS Topic - pub/sub model
- Amazon MQ
  - Uses open protocols to integrate with SQS and SNS (MQTT, AMQP, STOMP, Open wire, WSS)
  - Helps during a migration
- Cloud Integrations Summary:
  - ![](./img/Screenshot%202024-01-05%20at%2012.19.47 PM.png)

### 13. Cloud Monitoring

- CloudWatch Metrics
  - You can track Instance, Volume, ETC Metrics
- CloudWatch Alarms
  - You can trigger SNS Topics and more when certain metric conditions are met
- CloudWatch Logs
  - Allows for real-time monitoring of resources (EC2, EBS, RDS, SQS, SNS)
  - For EC2, needs to be configured with a CloudWatch Logs Agent
    and proper IAM Permissions via IAM Roles
- Amazon EventBridge
  - formerly CloudWatch Events
  - Good for CRON jobs or Event-based trigger Lambda functions (EventBridge Scheduler )
  - Default Event Bus
  - Partner Event Bus (3rd party events)
- CloudTrail
  - Provides governance, compliance, and audit for your AWS Account
  - An history of events / API calls made within your AWS Account
- X-Ray Overview
  - Hard to track logs on distributed systems
  - Can track requests and allows for troubleshooting
- CodeGuru Overview
  - ML-powered service
  - Automated code reviews and application performance recommendations
  - CodeGuru Reviewer - AI checks code quality
  - CodeGuru Profiler - checks performance runtime performance
- AWS Health Dashboard
  - Service History - shows all regions, all services
  - AWS **Account** Health Dashboard - shows your own services
- Cloud Monitoring Summary
  - ![](./img/Screenshot%202024-01-05%20at%202.53.33 PM.png)

### 14. VPC & Networking

- Virtual Private Cloud (VPC)
  - quite complicated - more needed for Solutions Architect and SysOps
  - at CCP-level:
    - VPC, Subnets, Internet Gateways & NAT Gateways
    - Security Groups, Network ACL (NACL), VPC Flow Logs
    - VPC Peering, VPC Endpoints
    - Site to Site VPN & Direct Connect
    - Transit Gateway
- IPv4 -> Internet Protocol version 4 (xxx.xxx.xxx.xxx) 4.3 Billion Addresses
- Elastic IP -> allows you to attach a fixed public IPv4 address to EC2 instance
- IPv6 -> 3.4 x 10^38 addresses
- VPC & Subnets Primer
  - VPC - Virtual Private Cloud
  - Subnets (public and private)
  - uses Route Tables
- Internet Gateway & NAT Gateways
  - helps VPC instances and subnets connect with the internet (via routes to Internet Gateway)
- NAT Gateways (AWS-managed) & NAT Instances (self-managed)
  - Useful to allow private subnets to have access to the internet while remaining private
- Each VPC can be attached to only 1 Internet Gateway
-
