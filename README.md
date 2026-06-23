
# 🛡️ CloudShield

## AWS Cloud Security Scanner

CloudShield is a cloud security assessment platform that helps identify security risks and misconfigurations in AWS infrastructure.

It scans AWS resources, analyzes security settings, and provides actionable recommendations to improve cloud security.

---

## 🎯 Objective

The goal of CloudShield is to simplify cloud security checks by automatically detecting common AWS configuration issues and presenting them through an easy-to-use dashboard.

---

## ✨ Features

### AWS Security Scanning
- Scan AWS resources
- Detect security misconfigurations
- Generate security findings

### Resource Analysis
- S3 bucket security checks
- IAM permission analysis
- Security Group analysis

### Security Reporting
- Risk classification
  - Critical
  - High
  - Medium
  - Low
- Security recommendations

### Dashboard
- View scan results
- Track security issues
- Monitor cloud security posture

---

## 🏗️ Architecture

```

User
|
v
React Dashboard
|
v
FastAPI Backend
|
v
AWS SDK (boto3)
|
v
AWS Resources

S3 | IAM | EC2 | Security Groups

```

---

## 🛠️ Technology Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- Recharts

### Backend
- FastAPI
- Python
- Pydantic

### Database
- PostgreSQL

### Cloud
- Amazon Web Services
  - IAM
  - S3
  - EC2
  - Security Groups

### Tools
- Docker
- GitHub Actions

---

## 📁 Project Structure

```

CloudShield/

├── backend/
│
├── frontend/
│
├── docs/
│
├── screenshots/
│
└── README.md

````

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/manyashri1901/CloudSheild.git
````

### Backend Setup

```bash
cd backend

python -m venv venv

pip install -r requirements.txt

uvicorn main:app --reload
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## 🗺️ Development Roadmap

### Phase 1: Core Scanner

* [ ] AWS authentication
* [ ] S3 security scanner
* [ ] IAM scanner
* [ ] Security Group scanner

### Phase 2: Dashboard

* [ ] Security findings dashboard
* [ ] Filtering and search
* [ ] Scan history

### Phase 3: Deployment

* [ ] Docker setup
* [ ] AWS deployment
* [ ] CI/CD pipeline

---

## 🔮 Future Improvements

* Multi-cloud support
* AI security assistant

---

## 👩‍💻 Author

Manya Shrivastava

---

## 📄 License

MIT License

---
