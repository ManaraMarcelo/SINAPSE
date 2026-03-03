# SINAPSE (System of Intelligence and Process Analysis with Structured Semantics) ⚖️🤖

> **Academic Disclaimer:** This project was developed as my Final Capstone Project (TCC) for my Systems Analysis and Development degree at FATEC. It represents the foundation of a LegalTech SaaS that I am continuously evolving.

![Build Status](https://img.shields.io/badge/Status-Academic_MVP-orange)
![Stack](https://img.shields.io/badge/Stack-FastAPI%20|%20React%20|%20PostgreSQL-blue)
![Focus](https://img.shields.io/badge/Focus-LegalTech%20|%20RAG%20|%20AI-green)

---

### [📺 Watch the Product Demo](LINK_DO_VIDEO_AQUI)

---

## 🏗️ Architectural Overview

SINAPSE is a B2B SaaS platform designed to transform static legal PDFs into a structured, searchable, and permanent intelligence engine.

### 💻 Frontend: Component-Based Architecture
- **Stack:** React + Vite + TypeScript (powered by **Bun**).
- **Design:** Modern UI with **Tailwind CSS & Shadcn/UI**.
- **Logic:** Business logic is decoupled into Custom Hooks for better maintainability.

### ⚙️ Backend: Layered Pattern (Router-Service-Repository)
- **Stack:** **FastAPI (Python)** + LangChain.
- **Layers:** Clear separation between API routes, AI service logic, and database repositories using SQLAlchemy.

---

## 🚀 Key Technical Features

### 1. Permanent Semantic Memory (RAG)
![Vetorização em tempo real](LINK_DO_GIF_UPLOAD)

Unlike transient chatbots, SINAPSE builds a permanent database of legal knowledge using **Vector Search** (pgvector). It finds deep context in thousands of pages, not just keyword matches.

### 2. Automated Legal Metadata Extraction
![Dashboard de Metadados](LINK_DA_FOTO_DASHBOARD)

The system parses raw PDF text and extracts structured JSON objects, allowing for statistical analysis of legal cases.

### 3. Hard Grounding & Anti-Hallucination
To ensure legal reliability, every AI response includes **direct citations**. Users can click a source and verify the exact page where the information originated.

---

## 🛠️ Current Technology Stack
- **Frontend:** React, TypeScript, Bun, Tailwind CSS.
- **Backend:** Python, FastAPI, LangChain, PyMuPDF, SQLAlchemy.
- **Database:** **Neon.tech** (PostgreSQL Serverless + `pgvector`).
- **AI Engine:** OpenAI API (Embeddings & GPT-4o).

---

## 🗺️ Roadmap & Future Evolution (The Next Steps)

This project is in continuous development. My goal is to evolve this academic MVP into a production-ready enterprise solution.

- [ ] **Cloud Migration:** Transitioning storage and compute to **AWS** (S3 for documents and Lambda/ECS for scaling).
- [ ] **Infrastructure as Code:** Implementing Terraform for environment management.
- [ ] **Advanced Security:** Integration of AWS Cognito for enterprise-grade authentication.
- [ ] **Performance:** Implementing Redis caching for frequent semantic queries.

---

## ✉️ Contact & Links
**Marcelo Abreu** - Junior Data Scientist | ADS Student
[LinkedIn](https://www.linkedin.com/in/marcelo-manara) | [GitHub](https://github.com/ManaraMarcelo) | [Portifolio](https://portifolio-peach-beta.vercel.app/)