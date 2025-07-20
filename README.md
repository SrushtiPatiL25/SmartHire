   # SmartHire: Resume & JD Matcher with AI 🤖

An intelligent, full-stack job matching application that helps job seekers and recruiters by comparing resumes with job descriptions using AI for better fit analysis.

---

## 🔍 Problem Statement

Recruiters often spend hours manually filtering resumes that match a job description. On the other hand, job seekers struggle to tailor their resumes for each job. This project aims to bridge the gap by using AI to automate the matching process and provide helpful feedback to both parties.

---

## 🎯 Features (Planned)

- Upload resume (PDF/DOCX)
- Paste or upload job description
- AI-powered matching score
- Visual feedback on mismatches and suggestions
- Recruiter dashboard: View top-matched resumes
- Candidate dashboard: Track applications and resume strength
- Authentication & role-based access
- Save job-resume pairs for future reference

---

## 🛠️ Tech Stack

| Layer        | Tech                  | Role |
|--------------|------------------------|------|
| Frontend     | React.js, Tailwind CSS | UI for job seekers & recruiters |
| Backend      | Java (Spring Boot)     | API to handle resume parsing, JD processing, scoring, auth |
| AI Matching  | OpenAI or NLP tools    | Match resume vs JD (extract key skills/requirements) |
| Storage      | MongoDB / PostgreSQL   | Resume, JD, scores, users |
| File Uploads | AWS S3 / Firebase      | Store uploaded resumes |
| Auth         | JWT / Firebase Auth    | Secure login for both roles |
| DevOps       | GitHub + GitHub Actions | Auto-deploy, CI/CD |
| Hosting      | Render / Railway / Vercel | Host backend and frontend separately |

---


