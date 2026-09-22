# AI Job Preparation Platform

> An AI-powered full-stack web application for resume analysis, job-description matching, interview preparation, and ATS-focused career assistance.

## 🚧 Project Status

**Ongoing Development**

This project is being developed as a full-stack GenAI application to help students and job seekers prepare for software engineering roles through AI-powered resume and interview analysis.

---

## 📌 Overview

The **AI Job Preparation Platform** allows users to analyze their resumes against specific job descriptions and receive personalized insights for interview preparation.

The platform aims to provide:

- Resume analysis
- Job description analysis
- Skill-gap identification
- AI-generated interview questions
- Technical and behavioral interview preparation
- ATS-oriented resume optimization
- Personalized preparation recommendations

The application combines a modern React frontend with a Node.js/Express backend and Google's Gemini API for AI-powered analysis.

---

## ✨ Features

### 🔐 Authentication
- User registration and login
- JWT-based authentication
- Protected application routes
- Secure user session handling

### 📄 Resume Analysis
- Resume upload and processing
- Resume content extraction
- Resume analysis based on target job descriptions
- Identification of relevant technical skills

### 💼 Job Description Analysis
- Analyze job descriptions
- Compare required skills with the user's resume
- Identify missing or weak skills
- Generate personalized preparation recommendations

### 🤖 AI-Powered Interview Preparation
- Generate technical interview questions
- Generate behavioral interview questions
- Generate questions based on identified skill gaps
- Create personalized interview preparation plans

### 📝 ATS Resume Optimization
- Analyze resume content against job requirements
- Identify missing keywords and skills
- Generate optimized resume content for specific job descriptions

### 📊 Interview Reports
- Match/compatibility analysis
- Technical skill assessment
- Skill-gap analysis
- Personalized preparation recommendations

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS
- React Router

### Backend
- Node.js
- Express.js
- REST APIs

### Database
- MongoDB
- Mongoose

### Authentication
- JSON Web Tokens (JWT)

### AI
- Google Gemini API

### Additional Technologies
- Puppeteer
- Git
- GitHub

---

## 🏗️ Application Architecture


                ┌──────────────────────┐
                │      React.js        │
                │      Frontend        │
                └──────────┬───────────┘
                           │
                           │ REST API
                           ▼
                ┌──────────────────────┐
                │    Node.js +         │
                │    Express.js        │
                └───────┬───────┬──────┘
                        │       │
              ┌─────────┘       └──────────┐
              ▼                            ▼
     ┌─────────────────┐          ┌─────────────────┐
     │    MongoDB      │          │  Gemini API     │
     │   + Mongoose    │          │   AI Analysis   │
     └─────────────────┘          └─────────────────┘
                        │
                        ▼
                ┌─────────────────┐
                │ Resume / JD     │
                │ Processing      │
                └─────────────────┘
