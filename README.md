# 🚀 NEXT HIRE – Intelligent AI-Based Placement Recommendation System

## 📌 Overview
**NEXT HIRE** is a centralized, AI-powered platform designed to automate and enhance campus placement processes. It integrates **automation, data synchronization, and Natural Language Processing (NLP)** to provide **personalized job recommendations** for students.

The system bridges the gap between **student skills and industry requirements** using semantic matching instead of traditional keyword-based filtering.

---

## 🎯 Problem Statement
Traditional placement systems:
- Rely on manual data handling  
- Use basic keyword matching  
- Lack real-time updates  
- Provide no personalization  

👉 Result: Inefficient job matching and missed opportunities

---

## 💡 Solution
NEXT HIRE addresses these issues by:
- Automating job data collection  
- Dynamically updating student profiles  
- Using AI/NLP for semantic matching  
- Providing real-time notifications  

---

## 🧠 Key Features

### 🔹 AI-Based Job Matching
- Semantic similarity using **SBERT embeddings**
- Accurate matching beyond keywords

### 🔹 Automated Job Aggregation
- Web scraping using **Puppeteer / Playwright**
- API-based job data integration

### 🔹 Profile Enrichment
- Academic data extraction using **Tesseract OCR**
- Coding platform integration (LeetCode, GFG)

### 🔹 Smart Ranking System
- Hybrid scoring based on:
  - Skills similarity  
  - CGPA  
  - Branch eligibility  

### 🔹 Notification System
- Email alerts for job matches  
- Real-time updates  

### 🔹 Role-Based Dashboards
- Student Dashboard  
- Staff Dashboard  
- Admin Dashboard  

---

## 🏗️ System Architecture

- **Frontend:** React.js  
- **Backend:** Node.js + Express  
- **AI Engine:** FastAPI (SBERT, FAISS)  
- **Automation Layer:** Cron jobs, scraping, OCR  
- **Database:** MongoDB Atlas  

---

## ⚙️ Tech Stack

### 💻 Frontend
- React.js  
- Tailwind CSS  
- Chart.js  

### 🔙 Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  

### 🤖 AI & NLP
- FastAPI  
- Sentence-BERT (SBERT)  
- FAISS  
- spaCy / NLTK  

### 🔄 Automation & Tools
- Puppeteer / Playwright  
- node-cron  
- Tesseract OCR  
- Axios  

### 🔐 Security
- JWT Authentication  
- bcrypt  
- OWASP practices  

---

## 🔄 Workflow
---

## 🧮 Ranking Formula

---

## 🗄️ Database Design

Main Collections:
- User  
- StudentProfile  
- Job  
- Match  
- Application  
- Notification  
- Logs  

---

## 🧪 Testing

- Unit Testing  
- Integration Testing  
- System Testing  

Includes:
- Test cases  
- Bug tracking  
- Execution reports  

---

## 📸 Screenshots

_Add screenshots here (Dashboard, Job Recommendations, Admin Panel, etc.)_

---

## 🚀 Installation & Setup

### 🔹 Prerequisites
- Node.js  
- Python (3.8+)  
- MongoDB  

### 🔹 Clone Repository
```bash
git clone https://github.com/your-username/next-hire.git
cd next-hire

cd backend
npm install
npm start

cd frontend
npm install
npm start

cd ai-service
pip install -r requirements.txt
uvicorn main:app --reload

