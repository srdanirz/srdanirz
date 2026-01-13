# Hi, I'm Daniel Ramírez

**Cloud & Platform Engineer** from Chile. Started debugging with Stack Overflow, Reddit, and random GitHub repos before AI was a thing. Now a vibecoder who mass-prompts until it works, then mass-prompts again when it doesn't. 🇨🇱 🇳🇱

I've built and shipped **$66K+ ARR** in SaaS products from scratch — from scraping sneaker sites at 3am to architecting cloud platforms. Most of my infrastructure experience is on **AWS**. Currently focused on cloud architecture, distributed systems, and convincing LLMs to write working code on the first try (still failing at that last one).

---

## Tech Stack

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Backend**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**AI & LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D4A574?style=flat-square&logo=anthropic&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Twelve Labs](https://img.shields.io/badge/Twelve_Labs-000000?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-FFFFFF?style=flat-square&logo=ollama&logoColor=black)

**Data, Scraping & Automation**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Web Scraping](https://img.shields.io/badge/Web_Scraping-47A248?style=flat-square&logo=selenium&logoColor=white)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Discord Bots](https://img.shields.io/badge/Discord_Bots-5865F2?style=flat-square&logo=discord&logoColor=white)
![WhatsApp API](https://img.shields.io/badge/WhatsApp_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)

---

## Featured Projects

### [NuMarket.app](https://numarket.app) — *Founder (2025 - Present)*
> Chilean market intelligence platform with real-time rankings, financial metrics, and AI-generated news

- **Stack:** Next.js 16, React 19, AWS Lambda, RDS PostgreSQL, Cognito, Terraform
- Custom Coin360-style treemap visualization algorithm
- 23 serverless functions with automated data pipelines
- Real-time stock tracking of 150+ Chilean companies
- AI news generation with Claude + daily market images with Gemini

---

### [Sponsy](https://sponsy.cl) — *Co-Founder & Tech Lead (2025 - Present)*
> AI-powered marketing platform connecting brands with real people for authentic campaigns in Chile

- **Stack:** React 18, Supabase, AWS Lambda, WhatsApp Cloud API, Azure OpenAI
- Backed by **Google for Startups**, **AWS for Startups**, and **Microsoft for Startups** credits
- 90% process automation through WhatsApp bots
- Multi-cloud AI strategy (Azure OpenAI + AWS Bedrock) with circuit breaker failover
- Video analysis pipeline with Twelve Labs for content validation

---

### [Vyper](https://whop.com/vyperpro) — *Founder (2023 - 2025)* `$36K ARR`
> Desktop app + browser extension for automated ticket purchasing at scale

- **Stack:** Go, Electron, React, Chrome Extensions, WebSockets
- Queue-it virtual queue management with anti-detection mechanisms
- Real-time task monitoring (600+ concurrent operations)
- Circuit breaker pattern + rate limiting + TLS fingerprinting
- Multi-site support (PuntoTicket, Ticketmaster) with plugin architecture

---

### [Rebel Notify](https://github.com/srdanirz/rebelnotify) — *Founder (2020 - 2023)* `$30K ARR`
> Chilean sneaker cookgroup with 100+ monthly subscriptions

- **Stack:** Python, BeautifulSoup, Discord.py, Chrome Extensions
- Real-time monitoring of 5+ Chilean retailers (Nike, Bold, Moredrops)
- Advanced anti-bot evasion (Cloudflare bypass, TLS fingerprinting, proxy rotation)
- Chrome extension for checkout automation with form auto-fill
- Multi-threaded architecture monitoring 100+ products simultaneously

---

### [ImageToText Solver](https://github.com/srdanirz/imagetotext-solver)
> Self-hosted OCR API for captcha solving with 90% cost reduction vs commercial services

- **Stack:** Node.js, Express, Tesseract.js, Azure Container Apps, Service Bus, Redis
- Distributed architecture with auto-scaling workers (0-500 replicas)
- Smart caching with 80-90% hit rate via image hash deduplication
- Load tested at 100k requests in 5 minutes
- Complete Terraform IaC for reproducible deployments

---

### Grady — *University Project (Inactive)*
> AI-powered exam correction platform for Chilean universities

- **Stack:** FastAPI, React 18, PostgreSQL, OpenAI, Anthropic, Google Vision
- Multi-engine OCR pipeline (Tesseract, Google Vision, Mathpix)
- Confidence scoring system with auto-approval thresholds
- Async architecture supporting 1000+ concurrent corrections

---

## Education

**Universidad Adolfo Ibáñez** — Industrial Engineering (Minor in Data Science) `2021 - 2025`

**Erasmus University Rotterdam** — Exchange Program `2024 - 2025`

---

## Certifications

- Microsoft Azure Data Fundamentals
- Microsoft Excel Expert

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/danielramirezfernandoy/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daniel@sponsy.cl)
