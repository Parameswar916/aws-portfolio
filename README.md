# ☁️ AWS Cloud Portfolio

> Built from scratch during the 12-Week AWS Speed Run (March–June 2026)

[![Live Demo](https://img.shields.io/badge/Live_Demo-00d4ff?style=for-the-badge&logo=github&logoColor=white)](https://parameswar916.github.io/aws-portfolio)
[![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](http://52.64.165.7)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/parameswar916)

---

## 🌐 Live URLs

| Platform | URL | Status |
|----------|-----|--------|
| GitHub Pages | [parameswar916.github.io/aws-portfolio](https://parameswar916.github.io/aws-portfolio) | 🟢 Always Live |
| AWS EC2 | [52.64.165.7](http://52.64.165.7) | 🟡 Learning Server |

---

## 🚀 What This Project Demonstrates

✅ EC2 Instance Launch & Configuration
✅ Amazon Linux 2023 Server Setup
✅ Apache Web Server Installation
✅ SSH Connection with Key Pairs
✅ IAM User & Security Groups
✅ Elastic IP Configuration
✅ GitHub Pages + CI/CD Auto-Deploy
✅ S3 Object Storage Concepts
✅ AWS Global Infrastructure Knowledge

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Cloud Provider | AWS (Amazon Web Services) |
| Compute | EC2 t3.micro |
| Operating System | Amazon Linux 2023 |
| Web Server | Apache httpd |
| Storage | AWS S3 |
| CDN/Deploy | GitHub Pages + GitHub Actions |
| Security | IAM + MFA + Security Groups + Key Pairs |
| Region | ap-southeast-2 (Sydney) |

---

## 📁 Project Structure
aws-portfolio/
│
├── index.html          # Main portfolio page
│                       # Dark themed, responsive
│                       # Skills + Timeline + Server info
│
└── README.md           # This file

---

## ⚙️ How To Deploy This Yourself

```bash
# Step 1: Launch EC2 instance (Amazon Linux 2023, t3.micro)

# Step 2: SSH into your server
ssh -i your-key.pem ec2-user@YOUR-IP

# Step 3: Install Apache
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd

# Step 4: Deploy your HTML
sudo tee /var/www/html/index.html << 'EOF'
[Your HTML code here]
EOF

# Step 5: Open port 80 in Security Groups
# Step 6: Visit http://YOUR-IP
```

---

## 📊 AWS Architecture
Internet
│
▼
Security Group (Port 80 + 22)
│
▼
EC2 Instance (t3.micro)
│
▼
Apache Web Server
│
▼
Portfolio Website

---

## 🗓️ Journey Timeline

| Date | Milestone |
|------|-----------|
| March 2026 | Started AWS Speed Run from zero |
| Week 1 | Linux + Networking + EC2 deployed |
| Week 2 | S3 + GitHub Pages + CI/CD + Elastic IP |
| Week 3 | VPC + Networking (in progress) |
| Week 6 | AWS Cloud Practitioner (target) |
| Week 12 | AWS Solutions Architect (target) |

---

## 👨‍💻 About The Builder

**Parameshwara Prasad**
- 📍 Bengaluru, India
- 🎓 B.Tech CSE — JNTUH (2025)
- 💼 Data Analytics background (TATA + Deloitte)
- 🚀 Transitioning to Cloud & DevOps Engineering
- 📅 12-Week AWS Speed Run: March–June 2026

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-parameswar916-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/parameswar916)
[![GitHub](https://img.shields.io/badge/GitHub-Parameswar916-222222?style=flat&logo=github)](https://github.com/Parameswar916)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-00d4ff?style=flat&logo=githubpages)](https://parameswar916.github.io/aws-portfolio)

---

> *"From zero to cloud architect — one command at a time."* ☁️
>
> Built with zero prior cloud experience | Week 1 of 12 | March 2026
