# Hi, I'm Rohit Mathur 👋

**B.Tech Computer Science (2027) · Full-Stack / Backend Developer · Problem Solver**

I build practical, working software — from AI agent backends and realtime collaboration tools to microservices platforms. Currently focused on **DSA, backend engineering, system design and distributed systems**, and looking for **SDE / Software Development internships**.

[![Portfolio](https://img.shields.io/badge/Portfolio-myportfolio--rsm.in-2563eb?style=flat-square&logo=google-chrome&logoColor=white)](https://www.myportfolio-rsm.in/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rohit--mathur-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohit-mathur-9a80b2296/)
[![LeetCode](https://img.shields.io/badge/LeetCode-rohit026893-F79F1B?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/rohit026893/)
[![Email](https://img.shields.io/badge/Email-rohit%40myportfolio--rsm.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rohit@myportfolio-rsm.in)

---

## 🚀 About

- 🎓 B.Tech CSE at **KIET, Ghaziabad** — CGPA **7.5**, batch **2027**
- 💻 Strong interest in **backend engineering** and **full-stack product development**
- 🌐 Builds with **React, Next.js, Node.js, Express, TypeScript**
- 🗄️ Works with **MongoDB, PostgreSQL, Prisma, Redis**
- ⚙️ Builds **microservices, event-driven systems and Dockerized backends**
- 🤖 Integrates **LLMs and agent workflows (LangGraph)** into real products
- 🧩 Consistent **DSA practice** — Java, C++, Python
- 🔐 Interest in **web security and vulnerability testing**
- ☁️ **AWS Cloud** and **Cisco CCNA** certified
- 📍 Ghaziabad, India · Open to remote and on-site SDE internships

---

## 🛠️ Tech Stack

**Languages**
`JavaScript` `TypeScript` `Java` `Python` `C` `C++` `SQL`

**Frontend**
`React 19` `Next.js` `Vite` `Tailwind CSS` `HTML5` `CSS3` `Redux Toolkit`

**Backend**
`Node.js` `Express 5` `REST APIs` `Socket.IO` `JWT` `Clerk` `Firebase Auth` `Next.js Route Handlers`

**AI / GenAI**
`LangChain` `LangGraph` `Google Gemini` `Groq` `OpenRouter` `Tavily` `Puppeteer` `AI SDK`

**Databases**
`MongoDB` `MongoDB Atlas` `PostgreSQL` `Prisma` `Redis` `SQLite` `Neon`

**Infrastructure**
`Docker` `Docker Compose` `Kafka` `AWS` `Turborepo` `pnpm` `Git` `GitHub Actions` `PM2` `Caddy`

---

## 🔥 Featured Projects

### 🤖 [Covo AI Assistant](https://github.com/Rohit0265/Covo-AI-Assistant) — Multi-model AI platform on microservices

Production-grade AI chat platform: 4 independent Node services behind an Express API Gateway, multi-model chat (Gemini / Groq / OpenRouter), realtime web search, image + document generation, credit billing, and LangGraph agent workflows.

**Stack:** React 19 · Vite · Redux Toolkit · Tailwind v4 · Express 5 · MongoDB Atlas · Redis · LangChain/LangGraph · Firebase Auth · Razorpay · AWS S3 · PDFKit · Docker

- LangGraph state-machine agent orchestration (router + chat nodes)
- Microservices: gateway, auth, AI agent, and supporting services
- Token-based auth with Redis session caching, in-app credit purchases via Razorpay

---

### 🛒 [E-Commerce Platform](https://github.com/Rohit0265/E-Commerce-Platform) — Kafka-driven microservices monorepo

Full-stack commerce platform built as a Turborepo monorepo with 8 apps: `auth-service`, `product-service`, `order-services`, `payment-service`, `email-service`, `kafka-broker`, plus `client` and `admin` frontends. Services communicate asynchronously over Kafka.

**Stack:** TypeScript · Next.js · Turborepo · pnpm workspaces · Kafka · Docker Compose · PostgreSQL (Neon) · Caddy · PM2

- Event-driven service communication, independent deployables
- Dockerized build + Caddy reverse proxy + PM2 process management

---

### ⚡ [SyncCode](https://github.com/Rohit0265/SyncCode) — Real-time collaborative coding workspace

Low-latency, conflict-free multi-user code collaboration in the browser — Yjs CRDTs over Socket.IO, Monaco Editor (the VS Code engine), live presence/awareness sidebar, Dockerized.

**Stack:** React 19 · TypeScript · Vite · Monaco Editor · Yjs (CRDTs) · y-monaco · Socket.IO · Tailwind v4 · Docker

- CRDT-based document sync — zero merge conflicts on concurrent edits
- Live collaborator presence and connection status

---

### 🚀 [PrepAI](https://github.com/Rohit0265/PrepAI) — GenAI interview coach & resume builder

Analyzes a resume, self-description and target JD to generate tailored technical + behavioral questions, sample answers, a day-by-day study roadmap, and an ATS-optimized PDF resume.

**Stack:** React (Vite) · Node.js · Express · MongoDB · Mongoose · Gemini 2.5 Flash · Puppeteer · TailwindCSS · JWT

- Zod-validated structured AI responses, server-side PDF generation
- Custom JWT auth; Chromium dependencies handled via Dockerized backend

---

### 💬 [QuickMe](https://github.com/Rohit0265/QuickMe) — Realtime social app with DMs

Full-stack photo/video social platform with a global feed, likes, comments, user search, public profiles, and real-time one-to-one messaging over Socket.IO.

**Stack:** React 19 · TypeScript · Vite · Tailwind v4 · Express 5 · MongoDB/Mongoose · Clerk · Cloudinary + Multer · Socket.IO

- Optimistic UI likes, inline video playback, persisted message history
- Protected routes on the frontend, auth middleware on the API

---

### 🎥 [YOOM — Meeting Platform](https://github.com/Rohit0265/YOOM-Meeting-Platform) — Zoom clone

Real-time video meeting platform: create and join secure meetings, server-side token generation, protected routing.

**Stack:** Next.js (App Router) · TypeScript · Clerk Authentication · Stream Video API

🔗 Live: [meeting-two-lac.vercel.app](https://meeting-two-lac.vercel.app/)

---

### 🎓 [Edmey — LMS Platform](https://github.com/Rohit0265/Edmey-Full-Stack-LMS-Platform) — Online learning management system

Dual-role LMS: students browse/enroll/watch courses and track progress; instructors create courses, upload content, organise lessons and monitor enrolments.

**Stack:** React · TypeScript · Tailwind CSS · React Router · Node.js · Express · MongoDB · Clerk

---

### 🤖 [SQL Agent AI SDK](https://github.com/Rohit0265/SQL-AGENT-AI-SDK) — Natural language → SQL

AI assistant that lets non-technical users query a database in plain English ("show me total sales for last month") — prompt → validated, read-only SQL → structured results.

**Stack:** React / Next.js · TypeScript · Node.js · SQLite · LLM API

- Read-only query mode, query validation layer, controlled schema access
- 🔗 Live: [sql-agent-plum.vercel.app](https://sql-agent-plum.vercel.app/)

---

### 🛠️ More Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [Blog App](https://github.com/Rohit0265/My-Blog-App) | Full-stack CRUD blogging platform with auth, search and profiles | React, Tailwind, Node, Express, MongoDB |
| [Password Manager](https://github.com/Rohit0265/Password-Manager) | Credential manager focused on auth flows, hashing and validation | React, Node, Express, MongoDB, bcrypt |
| [URL Shortener](https://github.com/Rohit0265/URL-SHORTNER) | Short link generator with redirect and async data flow | React, Tailwind, MongoDB |
| [Spotify Clone](https://github.com/Rohit0265/Music-Player-Spotify-Clone) | Functional music player with real audio playback controls | HTML5, CSS3, JavaScript · [Live](https://music-player-rsm.vercel.app) |

---

## 📚 Currently Learning

```
Data Structures & Algorithms
        ↓
Backend Architecture & APIs
        ↓
System Design
        ↓
Microservices & Distributed Systems
        ↓
Cloud, Docker & DevOps
```

What I'm most drawn to is **how scalable systems are designed** — not just which framework to use.

---

## 💡 What I Like Building

- AI-powered and agentic applications
- Backend APIs and microservices
- Real-time and collaborative tools
- Full-stack products end to end
- Security and vulnerability-testing utilities

---

## 🌐 Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/rohit-mathur-9a80b2296/)
- 🌐 [Portfolio](https://www.myportfolio-rsm.in/)
- 🧩 [LeetCode](https://leetcode.com/u/rohit026893/)
- 💻 [GitHub](https://github.com/Rohit0265)
- 📧 rohit@myportfolio-rsm.in · 📞 +91 95827 04516

---

### 🤝 Open to Opportunities

I'm looking for **SDE / Software Development internships** where I can contribute to real-world products, learn from experienced engineers, and grow as a backend or full-stack developer. If you're hiring or want to collaborate on a project, my inbox is open.

> **Build. Learn. Break. Fix. Repeat. 🚀**
