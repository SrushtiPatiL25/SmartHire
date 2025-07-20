# 🧠 System Design: AI-Powered Resume & JD Matcher

## 🎯 Project Goal

To build a web platform that uses AI to match candidate resumes with job descriptions (JDs) based on skills, experience, and relevance. It helps **job seekers** get better job matches and **recruiters** identify ideal candidates efficiently.

---

## 🏗️ System Architecture Overview

````mermaid
flowchart TD
    UI[User Interface (React)] --> API[Backend API (Spring Boot)]
    API --> AUTH[Authentication (JWT)]
    API --> RESUME[Resume & JD Upload API]
    API --> MATCHER[Matching Engine (AI/NLP)]
    MATCHER --> LLM[OpenAI API or Local Model]
    API --> DB[(Database: PostgreSQL/MongoDB)]
    DB -->|Stores| DATA[User Info, Resumes, JDs, Match Results]
    API --> ADMIN[Admin & Analytics Panel]
