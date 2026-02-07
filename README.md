# 🚀 Elevatr – Job Portal Connecting Students with Recruiters

![Tech](https://img.shields.io/badge/Tech-MERN-blue)
![Frontend](https://img.shields.io/badge/Frontend-React%20%7C%20Vite-success)
![Backend](https://img.shields.io/badge/Backend-Node%20%7C%20Express-yellow)
![Database](https://img.shields.io/badge/Database-MongoDB-brightgreen)
![Status](https://img.shields.io/badge/Status-Active-success)

Elevatr is a **full-stack job portal platform** built to connect students with recruiters by streamlining job discovery, applications, and shortlisting.  
The platform also includes an **AI-based resume analysis feature** that helps evaluate whether a resume matches a given job description based on relevant keywords.

---

## 📌 Project Overview

Elevatr simulates a real-world recruitment workflow where:
- Students can explore job opportunities and apply
- Recruiters can post jobs and shortlist candidates
- Resume relevance is analyzed against job descriptions using keyword matching logic

The project focuses on **end-to-end full-stack development**, backend API design, frontend user experience, and basic AI-driven analysis.

---

## 🚀 Key Features

### 👩‍🎓 Student Features
- Student registration and login
- Browse available job postings
- Apply for jobs and upload resumes
- View application status

### 🧑‍💼 Recruiter Features
- Recruiter login and dashboard
- Post and manage job listings
- View applicants and shortlist candidates

### 🤖 AI Resume–JD Matching Feature
- Analyzes resume content against job descriptions
- Extracts and compares relevant keywords
- Helps indicate whether a resume aligns with job requirements
- Designed to assist screening (not automated rejection)

---

## 🛠 Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS

### Backend
- Node.js
- Express.js
- RESTful APIs

### Database
- MongoDB

### Tools & Utilities
- Git & GitHub
- Postman
- ESLint

---

## 📁 Project Structure (High Level)

```
Elevatr/
├── backend/
│ ├── config/ # Database & app configuration
│ ├── controllers/ # Request handling logic
│ ├── middlewares/ # Auth & request middleware
│ ├── models/ # MongoDB schemas
│ ├── routes/ # API routes
│ ├── uploads/ # Resume uploads
│ ├── server.js # Backend entry point
│ └── package.json
│
├── frontend/
│ ├── src/ # React components & pages
│ ├── index.html
│ ├── vite.config.js
│ ├── tailwind.config.js
  └── package.json
```

---

## 🔍 How the AI Resume Matching Works

1. Recruiter posts a job with required skills/description  
2. Student uploads a resume while applying  
3. Backend processes resume text  
4. Keywords from the job description are compared with resume content  
5. The system highlights alignment to assist recruiter decision-making  

⚠️ *This feature is meant for assistance, not automated hiring decisions.*

---

## 🎯 Learning Outcomes

- Built a complete **full-stack MERN application**
- Designed RESTful APIs for real-world workflows
- Implemented authentication and role-based access
- Integrated frontend with backend services
- Gained exposure to **AI-based keyword matching logic**
- Improved understanding of recruiter–candidate systems

---

## 📈 Future Enhancements

- Resume scoring and visualization
- Advanced NLP-based resume analysis
- Email notifications
- Deployment on cloud platform
- Role-based analytics dashboard

---

## 👩‍💻 Author

**Muskan**  
Computer Science & Engineering Undergraduate  
GitHub: https://github.com/muskan-1230  
LinkedIn: https://www.linkedin.com/in/muskan-jain-645144292
