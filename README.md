<!-- Typing Animation Banner -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1200&color=38BDF8&center=true&vCenter=true&width=750&lines=Hi+👋,+I'm+Mohammad+Mastur;Full-Stack+Engineer+%26+Backend+Architect;Building+Agentic+AI+%26+Multi-Tenant+SaaS;LangChain+%26+LangGraph+Orchestrator;Optimizing+High-Throughput+APIs+%26+Databases+⚡" alt="Typing SVG" />
</p>

<div align="center">

  <h1>👨‍💻 Mohammad Mastur</h1>
  
  <p>
    <strong>Full-Stack Engineer &bull; Backend Architecture &bull; GenAI & Agentic AI (LangChain / LangGraph)</strong>
  </p>

  <p>
    <a href="https://www.linkedin.com/in/mohammadmastur/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:bikanerwalamastur13@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://github.com/mohammadmastur"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  </p>

</div>

---

## 📌 Executive Summary

Full-Stack Software Engineer and BCA undergraduate at Swarrnim Startup & Innovation University, specializing in high-reliability backend engineering, isolated multi-tenant architectures, real-time distributed synchronization, and multimodal GenAI / Agentic systems. 

Experienced in architecting production-grade ERP and SaaS platforms featuring isolated database tenancy, 0ms Server-Sent Events (SSE) live counter broadcasting, Redis-backed asynchronous job queues (BullMQ), multimodal AI vision OCR document ingestion, and automated tax compliance pipelines. Actively engineering with **LangChain**, **LangGraph**, and autonomous multi-agent workflows.

---

## 🔭 Core Engineering Focus

| ⚙️ Backend & Systems | 🗄️ Database & Scaling | 🤖 GenAI & Agentic Systems |
| :--- | :--- | :--- |
| • **Multi-Tenant SaaS Isolation** | • **Compound & Geospatial Indexing** | • **LangChain & LangGraph Multi-Agent** |
| • **Redis & BullMQ Task Queues** | • **Redis In-Memory Caching** | • **Autonomous Agentic Tool-Calling** |
| • **High-Throughput REST APIs** | • **Document Aggregation Pipelines** | • **Gemini Multimodal Vision OCR** |
| • **JWT & RBAC Security Layer** | • **PostgreSQL Schema Design** | • **LLM Gateway Routing & RAG** |
| • **Event-Driven Architecture** | • **IndexedDB & Offline PWA Sync** | • **ML / DL Core Foundations** |

---

## 🚀 Featured Engineering Projects

### 🏛️ Multi-Tenant Enterprise AI-Powered ERP SaaS Platform
> **Cloud-native, offline-first Enterprise Resource Planning & POS Billing solution built for retail chains, wholesale distributors, and supermarkets.**

- **Multi-Tenant Data Isolation**: Engineered automated request-scoping middleware using `x-tenant-id` and JWT contexts, guaranteeing zero data cross-leakage across isolated store databases.
- **0ms Real-Time Counter Sync**: Built a unidirectional Server-Sent Events (SSE) stream engine broadcasting instant stock deductions across 10+ hardware billing terminals concurrently.
- **Multimodal AI OCR Receipt Scanner**: Integrated Google Gemini Vision API to parse raw physical invoices and receipts, automatically classifying and extracting line items, HSN codes, and tax rates into inward purchase books and expense ledgers.
- **Resilient Offline PWA Engine**: Implemented Service Worker caching and an IndexedDB transactional draft queue allowing uninterrupted POS checkouts during internet blackouts with automated background reconciliation upon reconnection.
- **Background Worker & Crons**: Deployed Redis and BullMQ queues for asynchronous PDF invoice rendering, subscription lifecycle monitoring, and direct WhatsApp receipt dispatching.
- **Compliance & Auditing Engine**: Engineered dynamic apparel GST slab calculation (5% vs 12% dynamic threshold) and automated 1-click GSTR-1 / GSTR-3B CA Audit Pack JSON exporters.

```
Stack: Node.js (v20+) • Express.js • React 19 • Vite 6 • MongoDB • Redis 7.2 • BullMQ • Google Gemini AI • Tailwind CSS v4 • PDFKit
```

---

### 🤖 Multi-Model AI Gateway & Chat Platform
> **Production-grade AI conversation platform with dynamic provider routing and unified multi-LLM orchestration.**

- **Dynamic Provider Routing Engine**: Built an intelligent backend dispatcher that routes client prompts between Google Gemini REST endpoints and OpenRouter's OpenAI-compatible aggregator.
- **Multi-Model Orchestration**: Supports zero-latency switching across Gemini 2.5 Flash/Pro, Llama 3.1 8B, Qwen 3 8B, DeepSeek, and GPT-4.1 within a unified chat workspace.
- **Fault-Tolerant API Layer**: Engineered custom `ProviderError` handlers with automated single-retry mechanisms, rate-limit shielding, and structured audit logging without credential leakage.
- **Interactive UI Architecture**: Implemented optimistic updates, syntax-highlighted code rendering, custom markdown parsing, and persistent MongoDB thread history.

```
Stack: React 18 • Vite • Tailwind CSS • Framer Motion • Node.js • Express.js • MongoDB • Google Gemini API • OpenRouter API
```

---

### 🍽️ Cloud-Native Restaurant ERP & Real-Time Kitchen Display System
> **Containerized enterprise restaurant operations platform featuring automated order state machines and kitchen telemetry.**

- **Containerized Microservice Deployment**: Orchestrated full-stack multi-container infrastructure using Docker, Docker Compose, and Nginx reverse proxy load balancing.
- **Real-Time Kitchen Display (KDS)**: Built bidirectional WebSocket streams (Socket.io) for instantaneous table-to-kitchen order routing and live order status state transitions.
- **Asynchronous Order Processing**: Integrated Redis and BullMQ background workers for automated thermal receipt generation and asynchronous image processing via Cloudinary.
- **Defense-in-Depth Security**: Implemented strict RBAC (Admin, Captain, Kitchen, Cashier), Helmet security headers, rate limiting, and Zod runtime schema validations.

```
Stack: Node.js • Express.js • MongoDB • Redis • BullMQ • Docker • Docker Compose • Nginx • Socket.io • Cloudinary • Winston
```

---

### ⚡ Vingo — Gig-Economy Logistics & Real-Time Delivery Aggregator
> **Hyperlocal food and grocery delivery network connecting consumers, merchant outlets, and courier fleets.**

- **Geospatial Proximity Matching**: Utilized MongoDB `2dsphere` geospatial indexing and spherical geometry queries to compute live driver allocation within sub-second thresholds.
- **Live Fleet Tracking**: Integrated Leaflet Maps with bidirectional Socket.io pipelines to render real-time courier telemetry and trip progress updates.
- **Tri-Party State Synchronization**: Architected a robust state machine managing concurrent lifecycles across Customer, Vendor, and Delivery Partner interfaces.
- **Payment Verification**: Integrated Razorpay payment webhooks with cryptographic signature verification for secure checkout settlements.

```
Stack: React.js • Node.js • Express.js • MongoDB • Socket.io • Leaflet Maps • Razorpay • Tailwind CSS
```

---

## 🛠️ Technology Matrix

<table align="center">
  <tr>
    <td align="center" width="130"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
    </td>
  </tr>
  <tr>
    <td align="center" width="130"><strong>Backend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express.js" />
      <img src="https://img.shields.io/badge/REST_APIs-02569B?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs" />
      <img src="https://img.shields.io/badge/Server--Sent_Events-000000?style=flat-square&logo=dependabot&logoColor=white" alt="SSE" />
      <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.io" />
      <img src="https://img.shields.io/badge/BullMQ-FF4438?style=flat-square&logo=ghost&logoColor=white" alt="BullMQ" />
      <img src="https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
    </td>
  </tr>
  <tr>
    <td align="center" width="130"><strong>Databases</strong></td>
    <td>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      <img src="https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white" alt="Mongoose" />
    </td>
  </tr>
  <tr>
    <td align="center" width="130"><strong>Frontend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
      <img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
      <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux" />
      <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" alt="Framer Motion" />
    </td>
  </tr>
  <tr>
    <td align="center" width="130"><strong>AI & Machine Learning</strong></td>
    <td>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
      <img src="https://img.shields.io/badge/LangGraph-000000?style=flat-square&logo=diagram&logoColor=white" alt="LangGraph" />
      <img src="https://img.shields.io/badge/Agentic_AI-FF6F00?style=flat-square&logo=probot&logoColor=white" alt="Agentic AI" />
      <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white" alt="Google Gemini" />
      <img src="https://img.shields.io/badge/OpenRouter-6366F1?style=flat-square&logo=openai&logoColor=white" alt="OpenRouter" />
      <img src="https://img.shields.io/badge/ML_%2F_DL_Core-3776AB?style=flat-square&logo=python&logoColor=white" alt="ML/DL" />
      <img src="https://img.shields.io/badge/Multimodal_OCR-00A67E?style=flat-square&logo=tesseract&logoColor=white" alt="OCR" />
    </td>
  </tr>
  <tr>
    <td align="center" width="130"><strong>DevOps & Tools</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
      <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white" alt="Cloudinary" />
    </td>
  </tr>
</table>

---

## 📈 Active Engineering Focus

- **Agentic AI & Graph Orchestration**: Building cyclical multi-agent workflows with **LangGraph**, RAG pipelines with **LangChain**, autonomous tool-calling, and structured outputs.
- **Machine Learning & Deep Learning Foundations**: Strengthening foundational concepts in neural networks, embeddings, vector stores, transformer architectures, and LLM fine-tuning.
- **Distributed Systems & High Concurrency**: Deepening expertise in event-driven architecture, distributed caching layers, and horizontal database scaling.
- **Relational Mastery & Advanced Indexing**: Refining PostgreSQL schema normalization, foreign key constraints, ACID transaction isolation, and B-Tree index optimization.
- **Algorithmic Problem Solving**: Practicing Data Structures & Algorithms in C++ to sharpen complexity analysis and runtime optimization.

---

## 🤝 Connect & Collaborate

<div align="center">

  <p>
    Whether you are discussing backend architecture, system design, SaaS engineering, or modern full-stack development — feel free to reach out.
  </p>

  <a href="https://www.linkedin.com/in/mohammadmastur/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:bikanerwalamastur13@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>

  <br/><br/>
  
  <sub>Crafted with intent &bull; Designed for scale &bull; Optimized continuously</sub>

</div>
