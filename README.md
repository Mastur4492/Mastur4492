<!-- Typing Animation Banner -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=550&lines=Hi+👋,+I'm+Mohammad+Mastur;Full-Stack+MERN+Developer;Backend+Architecture+%26+APIs;Multi-Tenant+SaaS+Systems;GenAI+%26+Agentic+Workflows+🚀" alt="Typing SVG" />
</p>

<div align="center">

  <h1>👨‍💻 Mohammad Mastur</h1>
  
  <p>
    <strong>Full-Stack Developer &bull; Backend Engineering &bull; Database Design &bull; GenAI & Agentic Systems</strong>
  </p>

  <p>
    <a href="https://www.linkedin.com/in/mohammadmastur/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:bikanerwalamastur13@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://github.com/mohammadmastur"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  </p>

</div>

---

## 📌 About Me

Full-Stack MERN Developer and BCA student at Swarrnim Startup & Innovation University, with a strong focus on **backend architecture, database design, and real-world SaaS systems**. 

Experienced in building business applications with isolated multi-tenancy, real-time data sync, asynchronous job queues, and multimodal GenAI integrations. Currently exploring **LangChain, LangGraph, and Agentic AI workflows** alongside relational database optimization with PostgreSQL and DSA in C++.

---

## 🔭 Core Engineering Focus

| ⚙️ Backend & Architecture | 🗄️ Databases & Caching | 🤖 AI & Real-Time Systems |
| :--- | :--- | :--- |
| • RESTful API Design & Routing | • Compound & Geospatial Indexing | • Server-Sent Events (SSE) & Sockets |
| • Redis Caching & BullMQ Queues | • Dynamic Multi-Tenant Data Isolation | • Multimodal AI Vision OCR (Gemini) |
| • JWT Authentication & RBAC | • MongoDB Aggregations & Schema Design | • Multi-Model LLM Routing Gateways |
| • Background Workers & Crons | • PostgreSQL Schema & Query Design | • LangChain & LangGraph Workflows |
| • Offline PWA & Data Sync | • IndexedDB Client Storage Queues | • Webhook & Third-Party Integrations |

---

## 🚀 Featured Projects

### 🏛️ Multi-Tenant Enterprise AI-Powered ERP SaaS Platform
> **Cloud-native, offline-first ERP & POS billing solution designed for supermarkets, retail chains, and wholesale distributors.**

- **Tenant Isolation**: Implemented request-scoping middleware using `x-tenant-id` and JWT authorization to enforce strict database separation across merchant stores.
- **Real-Time Counter Synchronization**: Built a unidirectional Server-Sent Events (SSE) stream broadcasting instant inventory deductions across multiple POS hardware counters with zero polling overhead.
- **Multimodal AI OCR Ingestion**: Integrated Google Gemini Vision API to parse physical supplier invoices and expense receipts, auto-extracting line items, HSN codes, and GST rates into purchase ledgers.
- **Offline PWA Checkout**: Designed a Service Worker and IndexedDB transaction queue enabling cashiers to bill offline during network outages with automated conflict-free sync on reconnect.
- **Asynchronous Task Queues**: Configured Redis and BullMQ worker queues for asynchronous PDF invoice rendering, subscription expiration crons, and WhatsApp receipt dispatching.
- **Tax & Ledger Automation**: Engineered automated apparel GST slab calculation (5% vs 12% price thresholds) and 1-click GSTR-1 / GSTR-3B CA Audit Pack exports.

```
Stack: React 19 • Vite • Node.js • Express.js • MongoDB • Redis • BullMQ • Google Gemini AI • Tailwind CSS • PDFKit
```

---

### 🤖 Multi-Model AI Gateway & Chat Platform
> **Multi-LLM chat application with dynamic provider routing and unified model abstraction.**

- **Provider Abstraction Layer**: Built a unified backend dispatcher that routes prompts between Google Gemini REST endpoints and OpenRouter's API based on the selected model.
- **Multi-Model Support**: Supports dynamic switching across Gemini 2.5 Flash/Pro, Llama 3.1 8B, Qwen 3 8B, DeepSeek, and GPT-4.1 within a single interface.
- **Fault-Tolerant Request Handling**: Implemented custom `ProviderError` wrappers with automated retry logic, rate-limit protection, and structured logging.
- **Conversation State**: Manages persistent chat sessions in MongoDB with full Markdown and syntax-highlighted code rendering.

```
Stack: React 18 • Vite • Node.js • Express.js • MongoDB • Google Gemini API • OpenRouter API • Tailwind CSS • Framer Motion
```

---

### 🍽️ Restaurant ERP & Real-Time Kitchen Display System (KDS)
> **Full-stack restaurant operations platform managing real-time order states and kitchen workflows.**

- **Real-Time Order Routing**: Implemented bidirectional WebSocket streams (Socket.io) for instant table-to-kitchen order dispatch and live lifecycle state updates.
- **Containerized Architecture**: Deployed the multi-service backend, MongoDB, Redis, and frontend using Docker, Docker Compose, and Nginx reverse proxy routing.
- **Asynchronous Processing**: Integrated Redis and BullMQ background queues for automated thermal receipt generation and asynchronous media uploads via Cloudinary.
- **Role-Based Access**: Structured granular authorization across Admin, Captain, Kitchen, and Cashier roles with rate limiting and schema validations.

```
Stack: Node.js • Express.js • MongoDB • Redis • BullMQ • Docker • Docker Compose • Nginx • Socket.io • Cloudinary
```

---

### ⚡ Vingo — Real-Time Logistics & Food Delivery Platform
> **Hyperlocal delivery aggregator platform connecting customers, vendors, and delivery partners.**

- **Geospatial Proximity Matching**: Utilized MongoDB `2dsphere` geospatial indexing and queries to compute real-time driver matching based on store coordinates.
- **Live Fleet Tracking**: Integrated Leaflet Maps with Socket.io for live order broadcasting and courier location updates.
- **Multi-Role Coordination**: Structured state transitions across Customer, Vendor, and Courier interfaces for seamless order lifecycles.
- **Payment Verification**: Integrated Razorpay checkout with backend webhook signature validation.

```
Stack: React.js • Node.js • Express.js • MongoDB • Socket.io • Leaflet Maps • Razorpay • Tailwind CSS
```

---

## 🛠️ Technology Matrix

<table align="center">
  <tr>
    <td align="center" width="140"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Backend</strong></td>
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
    <td align="center" width="140"><strong>Databases</strong></td>
    <td>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      <img src="https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white" alt="Mongoose" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Frontend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
      <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux" />
      <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" alt="Framer Motion" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>AI & Machine Learning</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white" alt="Google Gemini" />
      <img src="https://img.shields.io/badge/OpenRouter-6366F1?style=flat-square&logo=openai&logoColor=white" alt="OpenRouter" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
      <img src="https://img.shields.io/badge/LangGraph-000000?style=flat-square&logo=diagram&logoColor=white" alt="LangGraph" />
      <img src="https://img.shields.io/badge/Agentic_AI-FF6F00?style=flat-square&logo=probot&logoColor=white" alt="Agentic AI" />
      <img src="https://img.shields.io/badge/Multimodal_OCR-00A67E?style=flat-square&logo=tesseract&logoColor=white" alt="OCR" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Cloud & DevOps</strong></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
    </td>
  </tr>
  <tr>
    <td align="center" width="140"><strong>Tools & Integrations</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
      <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white" alt="Cloudinary" />
      <img src="https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=3395FF" alt="Razorpay" />
      <img src="https://img.shields.io/badge/WhatsApp_API-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp API" />
      <img src="https://img.shields.io/badge/PDFKit-E01E5A?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="PDFKit" />
    </td>
  </tr>
</table>

---

## 📈 Active Engineering Focus

- **Backend Architecture & API Design**: Designing modular RESTful services, middleware pipelines, and scalable request validation.
- **Database Optimization & PostgreSQL**: Refining indexing strategies, relational schema design, transactions, and query performance.
- **Redis Caching & Background Queues**: Implementing in-memory caching patterns and BullMQ worker queues for asynchronous processing.
- **Agentic AI & LLM Workflows**: Building stateful multi-agent systems and RAG pipelines using **LangChain** and **LangGraph**.
- **Real-Time Communication**: Working with Server-Sent Events (SSE) and WebSockets for low-latency live synchronization.
- **DSA in C++**: Practicing data structures and algorithms to strengthen computational problem-solving and efficiency.

---

## 🤝 Connect & Collaborate

<div align="center">

  <p>
    Open to discussing backend architecture, SaaS development, full-stack systems, and AI engineering.
  </p>

  <p>
    <a href="https://www.linkedin.com/in/mohammadmastur/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    &nbsp;
    <a href="mailto:bikanerwalamastur13@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail" /></a>
  </p>

  <sub>Designed with intent &bull; Built for performance &bull; Optimized continuously</sub>

</div>
