## 🛠️ System Design: AI-Powered Resume & JD Matcher

```mermaid
flowchart TD
  UI[👩‍💻 User Interface (React)]
  API[🔗 Backend API (Spring Boot)]
  AI[🧠 AI Matching Engine (OpenAI/GPT)]
  DB[(🗃️ Database - MySQL/MongoDB)]
  FS[(📁 File Storage - AWS S3 / Local)]
  Admin[🧑‍💼 Admin Dashboard (React)]
  Auth[(🔐 Auth Service - JWT/OAuth2)]

  UI -->|Login/Upload Resume| Auth
  UI -->|Send Resume/JD| API
  Admin --> API
  API --> Auth
  API --> DB
  API --> FS
  API --> AI
  AI --> API
  API -->|Send Match Results| UI
