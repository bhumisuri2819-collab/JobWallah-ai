#  JobWallah – Your Path To Career Success

> **Build better resumes. Match smarter. Apply faster.**

A full-stack career productivity platform built using the **MERN stack**, designed to help users create multiple resumes, analyze job descriptions with AI, discover jobs, and track applications — all in one place.

---

##  Tech Stack

### Frontend
- **React** – Component-based UI
- **Tailwind CSS** – Utility-first styling
- **Zustand** – Lightweight global state management
- **Axios** – API communication with cookie support

### Backend
- **Node.js + Express** – REST API server
- **MongoDB + Mongoose** – Database & schema modeling
- **JWT Authentication** – Secure user sessions (cookie-based)
- **bcrypt** – Password hashing & security
- **Cookie-parser** – HTTP-only cookie handling
- **Google Generative AI (Gemini)** – AI-powered analysis & suggestions

### Job Discovery & Automation
- **LinkedIn Jobs API** – Job search aggregation
- **node-cron** – Scheduled background tasks (cleanup, sync jobs)

### File & Document Handling
- **Multer** – File upload handling
- **PDFKit** – Dynamic PDF generation (resumes, reports)

### Communication & Payments
- **Nodemailer** – Email notifications
- **Razorpay** – Subscription & premium plan payments

### Infrastructure & Architecture
- **CORS** – Secure cross-origin requests
- **dotenv** – Environment configuration
- **RESTful API design**
- **Modular MVC Architecture**

---

## Core Features

###  1. Resume Builder (Foundation)
- Create and manage **multiple resumes**
- Structured sections:
  - Skills
  - Experience
  - Education
  - Projects
  - Achievements
- Full **CRUD** support for resumes
- Clean separation of backend logic  
  _(model → controller → route)_

---

### 2. Job Description vs Resume (AI Analysis)
- Paste a job description and select a resume
- Backend extracts and normalizes skills
- AI-powered comparison engine:
  - **Match score calculation** 
  - **Missing skills detection** 
  - **Improvement suggestions** 

---

### 3. Job Search (Discovery)
- Search jobs from multiple sources
- View job details:
  - Company
  - Location
  - Apply link

---

###  4. Job Tracker (Application Management)
- Track all job applications in one place
- Application details:
  - Job title & company
  - Resume used
  - Status (Applied, Interview, Offer, Rejected, etc.)
  - Interview stage tracking
  - Referral info & notes
- Update application progress anytime
- **Plan-based limits**:
  - Free plan: up to **3 job searches per 24 hours**
  - Premium plan: **Unlimited job searches**

---

##  Authentication & Security
- Secure **cookie-based authentication**
- Protected routes using auth middleware
- User-specific data isolation  
  _(resumes, jobs, applications)_
- Ready for role-based expansion in future

---

## SnapShots

<p align="center">
<img src="https://drive.google.com/uc?export=view&id=1wCCWgpVjY5Qd6agIYtVF596WLY0SKQ28" width="800"/>
<img src="https://drive.google.com/uc?export=view&id=1pNA-4kS2dSfNndzHglPbl6Fvre5NxbJq" width="800"/>
<img src="https://drive.google.com/uc?export=view&id=1r1DNYyPY7onXQBldI-usCrsoO7sPy7_r" width="800"/>
  <img src="https://drive.google.com/uc?export=view&id=1rcEGhUg4ISqDMLLLPrIdwlVxJ5i6D3RK" width="800"/>
  <img src="https://drive.google.com/uc?export=view&id=1fHv9ruuLUnAFnwsa7i29bXzU9XxIjI3y" width="800"/>
  <img src="https://drive.google.com/uc?export=view&id=1vl-SWiBZX-foGRRSaiirJRqUVSL1_gaD" width="800"/>
  <img src="https://drive.google.com/uc?export=view&id=1fwtfsU32GUjfQ5HQInhPvw77tbgJGDUn" width="800"/>
  <img src="https://drive.google.com/uc?export=view&id=1CtUVaj3YFw6Oxzh65icpK3tpmuyvQVQz" width="800"/>
</p>

---
