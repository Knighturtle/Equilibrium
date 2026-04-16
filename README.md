# Equilibrium

![Python](https://img.shields.io/badge/Python-3.x-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Framework-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active_Development-brightgreen)
![AI](https://img.shields.io/badge/AI-Ollama-purple)

🚀 **Autonomous AI-Bookkeeping System**

Equilibrium is a next-generation AI bookkeeping system designed to maintain financial balance and integrity. 

## 🌌 Philosophy & Brand Identity

At the core of Equilibrium lies the **Antigravity** philosophy:
- **Elimination of Digital Gravity**: Freeing financial data from sluggish, centralized, and legacy systems, ensuring seamless and frictionless operations.
- **Adherence to Local Privacy**: Financial data is handled with the utmost security. Utilizing local LLMs via Ollama ensures that sensitive data never leaves your infrastructure. 

---

## 📌 Overview

Equilibrium is a modernized, intelligent, self-balancing engine. It acts as the vanguard of autonomous financial systems, providing instant technical transparency and empowering users with locally-run, privacy-first AI intelligence. 

---

## 🧱 Tech Stack

- **Core Engine (Backend)** → FastAPI
- **Database & ORM** → SQLModel
- **AI Processing** → Ollama (for Local LLM inference)

---

## 📂 Directory Structure

```text
Equilibrium/
├── app/                  # Core Engine
│   ├── ai/               # AI logic and local model integration
│   ├── templates/        # Application templates
│   ├── db.py             # Database integration
│   ├── main.py           # FastAPI application entry point
│   ├── models.py         # SQLModel database schemas
│   └── ollama_client.py  # Local LLM integration client
├── static/               # Frontend Assets
│   ├── app.js            # Client-side logic
│   └── style.css         # Styling rules
├── docker-compose.yml    # Service orchestration
├── Dockerfile            # Container configuration
└── requirements.txt      # Dependencies
```

---

## ⚙️ Setup

### Prerequisite

- Python 3.10+
- Ollama (for local AI features)

### 1️⃣ Environment Setup

```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# Linux/Mac
source .venv/bin/activate
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Application

```bash
uvicorn app.main:app --reload
```

The system will initialize at: `http://127.0.0.1:8000`

---

## 🗺️ Roadmap

- [ ] Complete AI automated reconciliation
- [ ] Implement secure containerized deployment (VPS/Docker)
- [ ] Expand frontend dashboard for real-time ledger viewing

---

## 👤 Author

Knighturtle

- GitHub: [@Knighturtle](https://github.com/Knighturtle)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
