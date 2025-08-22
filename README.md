# Abraham Rivera – Software Engineer  

![GitHub release (latest by date)](https://img.shields.io/github/v/release/abrahamrivera/awesome-solution)  
![License](https://img.shields.io/github/license/abrahamrivera/awesome-solution)  
![Stars](https://img.shields.io/github/stars/abrahamrivera/awesome-solution?style=social)  
![CI](https://github.com/abrahamrivera/awesome-solution/actions/workflows/ci.yml/badge.svg)

🚀 **Accelerating data‑driven products with clean, scalable APIs and intelligent search**  

---  

## 🎬 Demo  

<details>
  <summary>Click to view demo animation</summary>
  <p align="center">
    <img src="assets/demo.gif" alt="Demo animation showing API, UI and search flow" width="800"/>
  </p>
</details>

---  

## About  

I design end‑to‑end solutions that connect robust **.NET Core** and **Go** back‑ends to modern **React + TypeScript** / **Angular** front‑ends. By applying clean‑architecture principles, automated **n8n** workflows and **vector‑based semantic search**, I help companies turn raw data into actionable insight, shrink time‑to‑market and lower operational costs.  

---  

## ✨ Features  

- ✅ **Clean Architecture** – clearly separated layers (API, Application, Domain, Infrastructure)  
- 🔁 **.NET Core + Go** micro‑services for high‑throughput back‑end processing  
- 🌐 **React‑TS / Angular** SPA with lazy loading and state‑management (Redux Toolkit / NgRx)  
- 💾 **SQL Server & PostgreSQL** with migrations; PostgreSQL hosts **pgvector** for similarity search  
- 🤖 **n8n** workflows for automated ETL, notifications and scheduled jobs  
- 🔎 **Vector semantic search** (OpenAI embeddings + pgvector) for fast, fuzzy content discovery  

---  

## 🛠️ Tech Stack  

| Layer            | Technology                                   |
|------------------|----------------------------------------------|
| **API**          | .NET Core (WebAPI, Entity Framework Core)   |
| **Micro‑service**| Go (Gin)                                     |
| **Frontend**     | React + TypeScript, Angular                  |
| **Database**     | SQL Server, PostgreSQL (pgvector)            |
| **Automation**   | n8n                                          |
| **CI/CD**        | GitHub Actions, Docker, Docker‑Compose      |
| **Testing**      | xUnit, Jest, Cypress                         |

---  

## 🚀 Getting Started  

```bash
# 1️⃣ Clone the repository
git clone https://github.com/abrahamrivera/awesome-solution.git
cd awesome-solution

# 2️⃣ Build & run the whole stack with Docker Compose
docker compose up --build -d

# 3️⃣ Verify the API documentation
open http://localhost:5000/swagger   # macOS
# • On Windows use: start http://localhost:5000/swagger
# • On Linux open the URL in your browser manually
