# 🌐 Secure Static Portfolio on AWS (S3 + CloudFront)

This project demonstrates how to host a **production-grade static website** on AWS with a strong focus on **security and best practices**.

## 🚀 Architecture Overview

- Amazon S3 for static file storage
- Amazon CloudFront as CDN
- Origin Access Control (OAC) for secure access
- HTTPS enforced
- S3 bucket fully private (no public access)

## 🔐 Security Highlights

- Public access blocked at S3 level
- Bucket policy allows access ONLY from a specific CloudFront distribution
- Requests signed using SigV4 via OAC
- No public S3 URLs exposed

## 🧠 Why this matters

Most portfolios use public S3 buckets.  
This project shows **real-world AWS architecture** used in production environments.

## 🛠 AWS Services Used

- Amazon S3
- Amazon CloudFront
- IAM (Bucket Policy)
- Origin Access Control (OAC)

## 🌍 Live Demo

🔗 https://d2pzsz8dnihfuc.cloudfront.net/index.html

---

⭐ This project focuses on **security, scalability, and cost awareness**.
