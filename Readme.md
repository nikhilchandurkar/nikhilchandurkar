# Nikhil Chandurkar

### Python Backend Developer · Django · REST APIs · SQL

I build the backend services that banks rely on for KYC and loan decisions: fast, secure, and resilient when third-party vendors aren't.

Backend Developer at **Kalolytic Solution Pvt. Ltd.**, Pune (Feb 2026 – present), working with co-operative bank clients.

---

## What I've shipped at work

| Impact | How |
|---|---|
| **50+ REST endpoints** in production | Django/DRF APIs for *Data Marketplace*, the central KYC service behind a loan origination system |
| **20–40% lower vendor API costs** | Repeat KYC requests are served from stored responses keyed on PAN + DOB or Aadhaar, with a daily per-vendor cost report |
| **Fewer failed verifications** | Vendor timeouts now retry by reference ID, then fall back to a second vendor, with responses mapped to one structure |
| **~40–50 ms internal overhead** | Reference-ID and queue pattern, file-URL responses instead of base64, and trace IDs on every request |
| **Sensitive data protected** | JWT auth, request validation, AES encryption, and masking for Aadhaar and PAN |
| **On-premise delivery** | Deployed Django apps to bank servers with no internet access, with the bank's own certificates, alongside senior engineers |

---

## Work projects

**Data Marketplace** · Django, DRF, MySQL
One API for PAN, Aadhaar (OTP, OTP-less, DigiLocker), driving licence, voter ID, passport, RC, Udyam, GST, Form 26AS, ITR analytics, court-case, PEP, and AML checks. Also OCR and masking APIs (PaddleOCR, GLM-OCR) and per-bank usage and pricing tracking for billing.

**Bank Statement Analysis** · Django, Celery, Redis, PostgreSQL
Turns PDF and scanned statements into structured transactions and analytics (EOD balance, 50+ filters). Celery handles async processing, Redis serves recent reports with low latency, and bank-specific alert rules flag patterns like repeated cheque bounces.

**Early Warning System** · PostgreSQL, SQL
One of five engineers building the system's 43 rules; I researched, modelled, and implemented 6–7 of them as bulk-insert logic and SQL queries.

---

## Personal projects

- 🦷 **[Oroshine](https://github.com/nikhilchandurkar/oroshine)**: dental care appointment API with Google Calendar integration, Redis caching, and rate limiting (Django, PostgreSQL)
- 💬 **[Chat App](https://github.com/nikhilchandurkar/chat-app)**: real-time messaging with JWT auth, WebSockets, and persistent chat history (Django; first built on MERN)
- 🌱 **[Plant Disease Classifier](https://github.com/nikhilchandurkar/plant_disease_detector)**: ResNet50 in PyTorch across 38 disease classes, served through a REST API

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django%20REST-ff1709?style=flat&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

Also: JWT, AES encryption, data masking, third-party API integration, Postman, Git, Node.js/Express/React (MERN)

---

## Education

B.Tech, Artificial Intelligence and Data Science, Priyadarshini College of Engineering, Nagpur (2021 – 2025)

Currently going deeper on **system design** and **Django REST Framework**.

---

## Stats

![Stats](https://github-readme-stats.vercel.app/api?username=nikhilchandurkar&theme=midnight-purple&show_icons=true&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nikhilchandurkar&layout=compact&theme=midnight-purple&hide_border=true)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nikhil-chandurkar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/nikhilchandurkar)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:nikhilchandurkar24@gmail.com)
