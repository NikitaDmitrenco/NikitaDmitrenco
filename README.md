# Hi there, I'm Nikita Dmitrenco 👋
**Full-Stack Software Engineer & AI Systems Builder** specializing in modern TypeScript ecosystems, Next.js architecture, autonomous agent workflows, scalable web platforms, and data-intensive applications.

---

## 🎯 About Me
- 💻 Passionate about **modular system design**, type safety, clean architecture, and performance.
- 🛠️ Building full-stack web applications with **Next.js 16/14 (App Router), React 19/18, Node.js, TypeScript, Drizzle ORM, and PostgreSQL**.
- 📐 Focused on **robust engineering practices**: defensive server-side validation, integer minor-unit financial accounting, edge-level security, autonomous agent orchestration, and automated testing pipelines.
- 🌍 Designing accessible, internationalized (i18n), and responsive user experiences.

---

## 🚀 Featured Projects

### [Delo — AI-Powered Minimalist Task Manager](https://github.com/NikitaDmitrenco/delo) · [Live App](https://delo-dusky.vercel.app/) · [Telegram Bot](https://t.me/delo_task_bot)
> A minimalist AI-driven task orchestration system enabling frictionless task creation via Telegram (natural text & voice notes) and real-time synchronized Web dashboard with contextual deadline calculation.
- **Stack**: Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS v4, grammY, Supabase PostgreSQL, OpenAI GPT-4o-mini & Whisper, Vitest.
- **Key Engineering**:
  - **Dual Ingestion Pipeline (Voice & Text)**: Real-time Telegram audio ingestion (`.oga` streaming to OpenAI Whisper STT) combined with contextual NLP parsing (`gpt-4o-mini` with structured JSON schema and resilient Unicode Cyrillic offline fallback engine).
  - **Deterministic Timezone & Deadline Engine**: Precise wall-clock relative date/time resolution (anchored to user timezone) with strict no-hallucination policy (`deadline: null` when unspecified).
  - **Account Federation & Deep Linking**: Secure single-use cryptographic token protocol (`delo_<uuid>`) and 1-tap phone contact verification linking Telegram accounts to multi-tenant Supabase Auth profiles under PostgreSQL Row Level Security (RLS).
  - **Testing & Reliability**: 32/32 passing Vitest unit/integration tests with automated continuous deployment on Vercel.

### [Zento — Modern Multilingual E-Commerce Platform](https://github.com/NikitaDmitrenco/zento)
> An end-to-end digital technology e-commerce modular monolith with tri-lingual localization (RU, EN, RO), integer minor-unit pricing, edge-guarded RBAC, and server-authoritative checkout.
- **Stack**: Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS v4, Drizzle ORM, Supabase PostgreSQL, Vitest, Playwright.
- **Key Engineering**:
  - **Financial Integrity**: Zero IEEE 754 precision issues via integer minor units and immutable `order_items` price snapshotting.
  - **Security & RBAC**: Stateless JWT session pipeline in `httpOnly` cookies guarded at the perimeter with Next.js Edge Middleware.
  - **Testing**: 29 automated Vitest tests across 10 test suites, Playwright E2E coverage, and strict TypeScript/ESLint CI hygiene.

### [Aura — Autonomous AI Local Discovery Agent](https://github.com/NikitaDmitrenco/aura) · [Live Demo](https://aura-three-weld.vercel.app/)
> An AI-native autonomous discovery engine converting natural-language experiential requests into verified real-world places with semantic query expansion, 6-dimensional verification, reputation synthesis, and geospatial intelligence.
- **Stack**: Next.js 14 (App Router), TypeScript, Vanilla CSS Modules, OpenStreetMap Overpass API, Nominatim Geocoding, Leaflet, Server-Sent Events (SSE), Google Gemini / OpenAI.
- **Key Engineering**:
  - **Multi-Step Agent Architecture**: Autonomous loop coordinating intent parsing, multi-hypothesis semantic query expansion, geospatial entity deduplication (Haversine formula), and dynamic weighted intent-match scoring.
  - **Zero-Hallucination Claim Verification**: Rigorous 6-dimensional verification engine (*Identity, Location, Activity, Accommodation, Schedule, Atmosphere*).
  - **Real-Time Streaming & Geospatial UX**: Server-Sent Events (`ReadableStream`) streaming live agent step progression, interactive Leaflet map with CartoDB dark tiles, and multi-turn conversational memory with session state persistence.
  - **Testing**: 15/15 automated End-to-End scenarios test battery with 100% success rate and zero-config offline fallback mode.

---

## 🛠️ Core Tech Stack
```text
Languages:       TypeScript, JavaScript (ES2024+), SQL, HTML5, CSS3
Frontend:        React 19/18, Next.js 16/14 (App Router, Server Components), Tailwind CSS v4, Vanilla CSS Modules
Backend & APIs:  Node.js, Next.js Route Handlers, Server Actions, Server-Sent Events (SSE), REST APIs, Zod
AI & Agents:     Autonomous Agent Orchestration, Gemini API, OpenAI API, Semantic Search, Multi-Step Tooling
Databases & ORM: PostgreSQL, Supabase, Drizzle ORM, Drizzle Kit, Migrations & Indexing
Geospatial:      OpenStreetMap Overpass API, Nominatim Geocoding, Leaflet, Haversine Geo Calculation
Auth & Security: JWT (jose), bcryptjs, Edge Middleware, Role-Based Access Control (RBAC)
Testing & Tools: Vitest, Playwright, E2E Test Batteries, ESLint, Git, GitHub Actions, npm
```
