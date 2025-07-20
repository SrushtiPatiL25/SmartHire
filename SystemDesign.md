# 🧠 System Design: AI-Powered Resume & JD Matcher

## 🎯 Project Goal

To build a web platform that uses AI to match candidate resumes with job descriptions (JDs) based on skills, experience, and relevance. It aims to help **job seekers** get better job matches and **recruiters** identify ideal candidates efficiently.

---

## 🏗️ System Architecture Overview

```mermaid
graph TD
    A[User Interface (React)] --> B[Backend API (Java Spring Boot)]
    B --> C[Authentication Module]
    B --> D[Resume Upload / JD Upload]
    B --> E[Matching Engine (AI + NLP)]
    E --> F[OpenAI / LLM API or Local ML Model]
    B --> G[Database (PostgreSQL / MongoDB)]
    G --> H[User Info, Resumes, JDs, Matches]
    B --> I[Admin Dashboard & Analytics]
