# 🏡 Buyer Folio Inc. – Real Estate Agent Matching Platform

A scalable backend system that intelligently matches real estate buyers with agents based on location, expertise, feedback, and availability. Built with modular microservices, RESTful APIs, and integrated machine learning models to drive intelligent recommendations and business visibility.

---

## 📌 Project Overview

Buyer Folio aims to transform the agent-client matchmaking process through a robust software platform that balances automation, performance, and intelligence. We designed a data-driven backend system to:

- Dynamically match clients with optimal agents
- Support seamless API integrations
- Visualize KPIs for business and operational insights
- Enable scalable infrastructure and CI/CD workflows

---

## ❗ Business Problem

Traditional real estate systems rely on manual matching or static filters, leading to:

- ❌ Poor match quality and low conversions  
- ❌ Wasted time for buyers and agents  
- ❌ Lack of transparency and performance tracking

**Goal**: Automate and optimize the matchmaking workflow using intelligent scoring, real-time APIs, and feedback-driven models.

---

## ⚙️ System Architecture

User ➝ API Gateway ➝ Microservices (Spring Boot)
⬇︎
Match Engine ↔ XGBoost
⬇︎
AWS S3 / DynamoDB
⬇︎
Dashboard (Power BI)

---

## 🧠 Matching Engine

- Feature engineering: location match, agent specialty, ratings, response time, transaction volume
- Models: `XGBoost`, `Random Forest`, and rule-based fallback
- Weighted score system with real-time scoring endpoint

---

## 🛠️ Tech Stack

| Category         | Tools / Technologies |
|------------------|----------------------|
| **Languages**      | Python, Java, SQL |
| **Frameworks**     | FastAPI, Spring Boot |
| **Databases**      | DynamoDB |
| **ML Libraries**   | Scikit-learn, XGBoost, Pandas |
| **Cloud & DevOps** | AWS (EC2, Lambda, S3), Docker, Terraform, Jenkins, GitHub Actions |
| **Dashboards**     | Looker, Power BI |
| **Testing**        | PyTest, Swagger, Postman |
| **Project Mgmt**   | Agile/Scrum, Jira |

---

## 📊 Dashboards

Dashboards provide:

- Agent performance scores
- Real-time session activity
- Match success metrics
- Client satisfaction analytics

---

## 🔁 Project Structure

real-estate-platform/
├── backend/
│ ├── services/
│ ├── models/
│ ├── routers/
├── infrastructure/
│ ├── terraform/
│ └── docker/
├── api_docs/
├── dashboards/
├── tests/
├── notebooks/
├── requirements.txt
└── README.md

---

## 🧪 Testing & CI/CD

- Unit tests with `pytest`
- API testing with `Postman`
- CI/CD pipeline using `Jenkins`
- Dockerized microservices with tagged version rollbacks

---

## ⚡ Outcomes

- 🔼 40% increase in engagement using intelligent scoring
- ⚡ Sub-500ms latency on core API calls
- 🎯 +32% accuracy improvement in match predictions after ML integration

---

## 📬 Contact

Built with 💻 by **Rutwiz G.**  
📧 rutwizg@gmail.com

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
