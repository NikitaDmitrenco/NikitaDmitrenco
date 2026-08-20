# Hi, I'm Nikita Dmitrenco 👋

**Full-Stack Developer building AI-powered web products, automation and integrations.**

I turn product ideas into working full-stack applications using AI-assisted software development. My focus is on rapid product development — connecting modern frontends, server-side application logic, databases, APIs, AI capabilities, and external platforms like Telegram into cohesive, usable products.

---

## 🚀 Featured Projects

### 1. [Zento — Full-Stack E-Commerce Application](https://github.com/NikitaDmitrenco/zento)
> **Proof of complete full-stack web application development.**

Zento is a full-stack e-commerce application with product browsing, user accounts, shopping cart, checkout, orders, and an administrative interface.

- **What it demonstrates:**
  - Connecting UI → server-side application logic → database → authentication → business logic → admin management.
  - Multi-language catalog routing (`/en`, `/ru`, `/ro`) with localized content dictionaries.
  - Server-side order calculation using integer minor units (cents) for pricing consistency.
  - Protected admin panel for managing catalog items and tracking customer orders.
  - Interactive AI shopping assistant widget with catalog search and product recommendation cards.
- **Tech Stack:** Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS v4, Drizzle ORM, Supabase (PostgreSQL), Vitest (34 automated tests), Playwright.
- **Links:** [🛒 Live Storefront Demo](https://zento-blue.vercel.app) · [⚙️ Admin Panel](https://zento-blue.vercel.app/admin) · [📦 Source Code](https://github.com/NikitaDmitrenco/zento)

---

### 2. [Delo — Task Manager for Web + Telegram](https://github.com/NikitaDmitrenco/delo)
> **Proof of multi-system integration, Telegram bot development & AI parsing.**

Delo is a task manager that works seamlessly both as a web application and through Telegram. Users can create and manage tasks through natural text or voice messages, while the web dashboard provides a synchronized overview.

- **What it demonstrates:**
  - Multi-system integration pipeline: Telegram ↔ Telegram Bot ↔ backend logic ↔ AI parsing / Whisper speech-to-text ↔ structured task data ↔ Supabase PostgreSQL ↔ Web dashboard.
  - Ingesting Telegram text and `.oga` voice notes, transcribing via OpenAI Whisper, and extracting structured tasks (title, relative deadline, duration) with OpenAI GPT-4o-mini and Zod validation.
  - Account linking between Telegram and web users using phone contact verification and single-use token flows.
  - User data isolation via Supabase Auth and PostgreSQL Row Level Security (RLS).
- **Tech Stack:** Next.js 16/15 (App Router), React 19, TypeScript, Tailwind CSS v4, grammY (Telegram Bot framework), Supabase (PostgreSQL with RLS), OpenAI API (GPT-4o-mini & Whisper), Vitest (50 automated tests).
- **Links:** [🖥️ Live Web App](https://delo-dusky.vercel.app) · [🤖 Open Telegram Bot](https://t.me/delo_task_bot) · [📦 Source Code](https://github.com/NikitaDmitrenco/delo)

---

### 3. [Aura — AI-Powered Local Discovery](https://github.com/NikitaDmitrenco/aura)
> **Experimental / Learning Project.**

Aura is an experimental AI-powered local discovery project exploring multi-step search and agentic workflows. It was built as an exploration of how an AI system can combine user intent, external data, and multiple processing steps to produce recommendations.

- **What it explores:**
  - Multi-step search pipeline: natural language intent extraction, semantic query expansion, geospatial distance calculation, and structured claim verification.
  - Real-time step streaming to the client using Server-Sent Events (SSE).
  - Geospatial map visualization with Leaflet and OpenStreetMap Overpass integration.
- **Tech Stack:** Next.js 14, TypeScript, Supabase PostgreSQL, Leaflet, Server-Sent Events, OpenStreetMap Overpass API.
- **Links:** [🌐 Live Demo](https://aura-three-weld.vercel.app/) · [📦 Source Code](https://github.com/NikitaDmitrenco/aura)

---

## 🛠️ Technical Skills

### Core
TypeScript · JavaScript · React · Next.js (App Router)

### Backend & Data
Node.js · PostgreSQL · Supabase · Drizzle ORM · REST / API Development

### Product Development
Authentication & Sessions · CRUD Workflows · Admin Dashboards · E-Commerce Flows · Form Handling · Server/Client Communication

### AI & Integrations
OpenAI APIs (GPT-4o-mini, Whisper) · DeepSeek API · Structured AI Outputs (JSON schema) · Speech-to-Text · Telegram Bots (grammY)

### Testing
Vitest · Playwright · TypeScript Type Checking

---

## 💡 How I Work

I use AI-assisted development to move quickly from an idea to a working product. My strength is decomposing a product into frontend, backend, data and integration layers, implementing them, testing the main flows and iterating quickly.

I'm currently deepening my knowledge of production infrastructure, advanced security, system architecture and AI agent design.

---

## 📬 Contact & Opportunities

**Open to:**
- Full-stack development roles
- AI application development
- MVP & rapid product development
- Freelance & client projects
- Startup & product collaborations

- **GitHub:** [@NikitaDmitrenco](https://github.com/NikitaDmitrenco)

