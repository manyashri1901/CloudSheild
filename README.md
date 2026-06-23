CloudShield

CloudShield is a cloud security assessment platform that scans AWS resources for security misconfigurations and provides actionable remediation recommendations.

Overview

Cloud environments often contain misconfigured resources that can expose sensitive data or increase security risks. CloudShield helps identify these issues by scanning AWS resources and generating security findings through a centralized dashboard.

Features

 AWS Resource Discovery
 S3 Bucket Security Analysis
 IAM Security Analysis
 Security Group Analysis
 Risk Classification (Critical, High, Medium, Low)
 Security Recommendations
 Dashboard Visualization
 Scan History Tracking

 Tech Stack

 Frontend

 React
 Tailwind CSS
 Axios
 Recharts

Backend

FastAPI
 Python
 Pydantic

Database

PostgreSQL

Cloud Services

AWS
IAM
S3
EC2
Security Groups

AWS SDK
boto3

Deployment
Docker
AWS EC2
Project Structure
CloudShield/
│
├── frontend/
├── backend/
├── docs/
├── screenshots/
└── README.md
...
Roadmap

Phase 1 - Core Security Scanner

 AWS Authentication
 S3 Bucket Scanner
IAM Scanner
 Security Group Scanner

Phase 2 - Dashboard
 Findings Dashboard
 Severity Filtering
 Resource Search

Phase 3 - Deployment

 Docker Setup
 AWS Deployment
CI/CD Pipeline

Future Enhancements

 CIS Benchmark Checks
 SOC2 Compliance Checks
 Multi-Cloud Support (Azure/GCP)
 Automated Remediation Suggestions
 Email Alerting System

Author

Manya Shrivastava

## License

MIT License
