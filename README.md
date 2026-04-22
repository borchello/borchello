<div align="center">

# Boris Faktorovich

**AI Builder · Solo Product Engineer · Web3 Systems**

Designing and shipping full-stack AI-powered products end-to-end —
from system architecture to production deployment.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/bfaktor)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/jcooperstation)
[![TERMINAL](https://img.shields.io/badge/TERMINAL-runner.trade-brightgreen?style=flat&logo=googlechrome&logoColor=white)](https://runner.trade)

</div>

---

## Featured Projects

### TERMINAL — Intelligence-Driven Prediction Market Terminal
> TypeScript · React · Node.js · WebSocket · SSE · Polygon · GPT-4o · CLOB

Professional trading terminal for Polymarket built around information asymmetry as the only durable edge. Systematically converts real-world intelligence signals into actionable trade opportunities before the market prices them in.

- **ATLAS SIGINT Module** — 10 live intelligence sources: military aircraft (ADS-B), naval vessels (AIS), GPS jamming (GPSJam), satellite passes (CelesTrak), global news (GDELT), Telegram MTProto. EventFusionEngine clusters events within 500km / 2h window into confidence-scored FusionEvents
- **Oracle Signal Engine** — news-to-market prediction pipeline with Bayesian weight adaptation and accuracy tracking
- **Non-Custodial Trading** — browser-side session keys via Privy. Private keys never leave the device. Server cannot move USDC
- **Smart Copy Trading** — follows top-performing wallets with configurable risk management
- **Whale Intelligence** — real-time monitoring of trades ≥ $5K with trader profiling

`Production` · `Live users` · `Polymarket CLOB API` · `Privy Server Signers` · `ZeroDev AA` · [**→ runner.trade**](https://runner.trade)

---

### sol-arb — Solana MEV & Liquidation Engine
> Rust · Tokio · Geyser gRPC · Jito · Jupiter · Kamino · Kelly Criterion

Two independent on-chain engines running live on Solana mainnet.

- **DEX Arbitrage** — multi-hop path routing across Raydium, Orca, Meteora, Phoenix, Lifinity. Jito bundle submission with Kelly criterion tip sizing. Geyser gRPC for zero-lag pool state
- **Kamino Liquidation** — monitors ~100K lending obligations in real time. Predictive oracle modeling detects liquidatable positions before on-chain confirmation. Pre-built tx templates → < 1ms to finalize on trigger. Atomic liquidation + collateral swap via Jito

`Live mainnet` · `Sub-millisecond execution` · `Flash loan fallback (NAVI)`

---

### sui-arb — Sui Blockchain Arbitrage Bot
> Rust · Tokio · SPFA · CLMM · CLOB · AMM · Flash Loans · Prometheus

High-frequency arbitrage bot for the Sui blockchain.

- **Negative-cycle detection** via parallel SPFA across all pool types — tokens as nodes, pools as edges weighted by `-log(rate × (1 - fee))`
- **Execution** — flash loan (NAVI) → PTB build → Ed25519 sign → SHIO bundle or SIP-45 direct submit
- **DEX coverage** — Cetus (CLMM), Turbos (CLMM), DeepBook (CLOB), Kriya / FlowX / Aftermath (AMM)
- **Risk engine** — daily loss caps, per-trade limits, consecutive-failure circuit breaker
- **Observability** — Prometheus metrics, per-step pipeline tracing, Telegram alerts

`Live mainnet` · `Parallel SPFA` · `Full DEX coverage`

---

## Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| **Funding Arbitrage** | Delta-neutral funding-rate arbitrage across 13 CEX perpetual markets. Maker-first execution engine, orphan detection, live capital | Python · asyncio · 13 CEX APIs |
| **SENTINEL** | DeFi vulnerability hunting platform. 7-layer pipeline: static analysis → symbolic execution → formal verification → AI reasoning → PoC synthesis | Python · Slither · Halmos · Certora · Claude API · Neo4j · Temporal |
| **Bootstrapr** | AI mentor for indie founders. Aggregates 10K+ founder case studies into personalized playbooks with citations and next actions | Python · Claude API · pgvector · Voyage · Cohere · Langfuse |
| **DesignSpark** | Design-first AI web app builder. Turborepo monorepo with curated design systems and AI customization | Next.js 15 · React 19 · tRPC v11 · Drizzle · Fastify · Turborepo |
| **Domain Hunter** | Domain discovery and authority scoring. Crawls sources, parses zone dumps, scores via Ahrefs DR and Product Hunt signals | Python · Ahrefs API · WHOIS |

---

## Tech Stack

**Languages**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Move](https://img.shields.io/badge/Move-4DA2FF?style=flat&logo=sui&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**AI / ML**

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-412991?style=flat&logo=openai&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)

**Web3**

![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat&logo=solana&logoColor=white)
![Sui](https://img.shields.io/badge/Sui-4DA2FF?style=flat&logo=sui&logoColor=white)
![Polygon](https://img.shields.io/badge/Polygon-8247E5?style=flat&logo=polygon&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat&logo=ethereum&logoColor=white)
