# Boris Faktorovich

**AI Builder & Founder · AI Systems Architect · Solo Product Engineer**

Designing and shipping full-stack AI-powered products end-to-end — from system architecture to production deployment.

---

## Runner Terminal

> Real-time prediction market intelligence terminal built on [Polymarket](https://polymarket.com)

A professional-grade trading terminal with an embedded AI intelligence layer, signal engine, and copy trading automation — built solo from scratch.

---

## AI & Intelligence Systems

### Runner AI — Context-Aware Market Assistant
- **GPT-4o-mini** integration with multi-mode inference (`fast` / `research` / `markets`)
- Dynamic platform data snapshot injected into every prompt — model never hallucinates market data
- Cost-optimized token budgeting per mode ($0.00023–$0.00045/req)
- Rate limiting, request isolation, structured prompt engineering

### Oracle Signal Engine — Predictive Intelligence Pipeline
- Custom **signal detection algorithm**: news → entity extraction → market matching → confirmation
- Signals scored by confidence threshold (≥0.35) and confirmed via real-time price spike detection
- Full signal lifecycle: `PENDING → CONFIRMED → EXPIRED` with persistence
- **Correlation map**: cross-market signal amplification (related markets boosted on match)
- **Topic tracker**: detects recurring themes across news streams

### Adaptive Scorer — Bayesian Feature Weight Learning
- **Bayesian shrinkage algorithm** for self-improving signal accuracy over time
- Analyzes 30-day signal resolution history per entity feature type
- Formula: `w_eff = (k × prior + n × empirical) / (k + n)` — prevents overfitting on small samples
- Weight bounds ±50% of prior to prevent adversarial drift
- Persisted to DB, refreshed every 24h, served from in-memory cache

### Entity Extractor — Deterministic NLP Pipeline
- Dictionary + regex NLP engine (no LLM dependency — fast, zero cost, deterministic)
- Multilingual: **English, Russian, Hebrew, Arabic, Farsi** entity patterns
- Extracts: countries, people, organizations, topics, keywords, Twitter handles, Telegram references
- Military/geopolitical terminology taxonomy

### AI Briefing Service (SIGINT)
- Automated intelligence summaries every 30 min using **GPT-4o-mini**
- Triggered only when threat score > 0.40 (cost-gated)
- Output: SITREP → Key developments → Market implications → 24h threat outlook
- Graceful degradation to rule-based briefing if API unavailable

### Trader Analysis Engine
- Behavioral scoring: streak analysis, timing patterns, sizing consistency, drawdown profiling
- Bot detection heuristics, network analysis, benchmark comparison
- Portfolio-level analytics with calendar heatmaps and category breakdowns

---

## Trading & Web3 Infrastructure

- **Copy Trading Engine** — Privy Server Signers (non-custodial), virtual demo mode + live execution
- **CLOB Order Execution** — direct Polymarket API, browser-direct submission (datacenter geoblock bypass)
- **AA Wallets** — ZeroDev ERC-4337 account abstraction
- **Order Aggregator** — partial-fill deduplication for Polymarket CLOB
- **Real-time feeds** — WebSocket + SSE with heartbeat and WSS fallback chain
- **Audit Ledger** — immutable on-chain-style transaction log with reconciliation

---

## Tech Stack

**AI / Intelligence**
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o--mini-412991?style=flat&logo=openai&logoColor=white)
![Custom NLP](https://img.shields.io/badge/Custom_NLP_Pipeline-FF6B35?style=flat)
![Bayesian ML](https://img.shields.io/badge/Bayesian_Adaptive_Scoring-0066CC?style=flat)
![Signal Engine](https://img.shields.io/badge/Signal_Engine-22C55E?style=flat)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat)
![SSE](https://img.shields.io/badge/SSE_Streaming-FF6B35?style=flat)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white)
![Pino](https://img.shields.io/badge/Pino_Logger-green?style=flat)

**Database & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

**Web3 & Auth**
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat&logo=ethereum&logoColor=white)
![Privy](https://img.shields.io/badge/Privy_Server_Signers-6366F1?style=flat)
![ZeroDev](https://img.shields.io/badge/ZeroDev_AA_ERC--4337-FF6B00?style=flat)
![Wagmi](https://img.shields.io/badge/Wagmi_+_Viem-1C1C1C?style=flat)
![SIWE](https://img.shields.io/badge/SIWE-3C3C3D?style=flat)
![Polymarket](https://img.shields.io/badge/Polymarket_CLOB-0066FF?style=flat)

---

## Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=borchello&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=borchello&layout=compact&theme=dark&hide_border=true)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/bfaktor)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/jcooperstation)
