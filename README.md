<!-- ===================== BANNER ===================== -->

<p align="center">
  <img src="https://i.pinimg.com/1200x/34/71/ef/3471ef6a4dc1ebd88272db930088c40b.jpg" alt="lofi anime blue night" />
</p>

<p align="center">
  <i style="color:#7aa2f7;">Cracked dev. nerding out.</i>
</p>

---

<!-- ===================== ABOUT ===================== -->

<table>
<tr>
<td width="62%" valign="top">

<h2>About (自己紹介)</h2>

<p>I'm Rohit — a <b>backend & AI engineer</b> from Kolkata.</p>

<p>
I build backends that hold up — distributed services, realtime systems and LLM
agents with guardrails, evals and fallbacks under the hood. I care about the
parts nobody sees: service boundaries, queues, caches, rate limits, auth, and
what happens when a provider goes down. I build AI <i>into</i> systems, not
around them.
</p>

<p>
Computer Science (IoT, Cybersecurity & Blockchain) at Heritage Institute of
Technology · CGPA 9.02 · Smart India Hackathon 2025 national finalist.
</p>

<p>Things I keep circling back to:</p>

<p>
<code>Backend Engineering</code> · <code>Distributed Systems</code> ·
<code>LLM Agents</code> · <code>LangGraph</code> · <code>System Design</code> ·
<code>Realtime Systems</code> · <code>Retrieval & RAG</code> ·
<code>Reliability</code> · <code>Security</code> · <code>Evals & Observability</code>
</p>

<h2>📫 Connect With Me</h2>
<p align="left">
  <a href="https://portfolio-web-six-psi-43.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white">
  </a>
  <a href="https://linkedin.com/in/maity-rohit">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://x.com/turquoise_0904">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white">
  </a>
  <a href="https://www.instagram.com/rohit_0.0">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
  </a>
  <a href="https://discord.com/users/toiletduck69">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  </a>
  <a href="https://hashnode.com/@zaxx">
    <img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white">
  </a>
  <a href="https://www.threads.com/@zaxx.ewu">
    <img src="https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=threads&logoColor=white">
  </a>
  <a href="https://linktr.ee/zaxxewu">
    <img src="https://img.shields.io/badge/Linktree-43E55E?style=for-the-badge&logo=linktree&logoColor=white">
  </a>
  <a href="mailto:maityrohit021@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>
</td>
<td width="38%" valign="top" align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/watermelon588/watermelon588/main/assets/portrait-dark.png" />
  <img src="https://raw.githubusercontent.com/watermelon588/watermelon588/main/assets/portrait-light.png" width="100%" alt="" />
</picture>

</td>
</tr>
</table>

---

## In Numbers (数字)

| | |
|---|---|
| **16 kHz / 24 kHz** | PCM16 streaming pipeline with interruption flushing in KOE |
| **10 min** | persisted approval expiry with atomic claims on agentic writes |
| **188** | backend tests on TripVerse's deterministic planner |
| **35 / 35** | live-server WebSocket & WebRTC tests passing in Yap Chat |
| **5** | standalone design systems driven by one central content schema |
| **711** | API tests on Walkthru's agent platform |
| **13,311** | deep-sky objects scored live per request in SkyGuide AI |
| **24** | tools on a remote MCP server I built |
| **20 Hz** | sensor stream driving a realtime state machine |
| **23 / 23** | attack-probe checks passing on a Go server I hardened |

---

## Shipped (公開済み)

### 🧭 [Walkthru](https://github.com/watermelon588/Walkthru) — AI agent platform

A LangGraph browser agent that runs real user journeys inside your own Chrome. The API stays stateless (`interrupt()` / resume over HTTP, a Postgres checkpointer); jobs run from a durable Postgres queue (`FOR UPDATE SKIP LOCKED`, leases, jittered backoff); a circuit breaker sits across the model providers; the crawler is SSRF-hardened; and a remote MCP server exposes 24 tools. Every safety rule is enforced in code, never in the prompt. **711 API tests**, plus LangSmith evals on adversarial fixture sites.

`LangGraph` · `FastAPI` · `PostgreSQL` · `Supabase (RLS)` · `MCP` · `LangSmith` · `Chrome MV3`

### 🗺️ [TripVerse](https://tripverse-0.vercel.app) — agentic planner

Two LangGraph planning graphs write into one normalized trip document. Budget, routing cost and day capacity are deterministic code; models only propose. Graph updates stream over FastAPI, with per-node model routing and a Groq → Groq → Gemini fallback on rate limits. **188 backend tests.** [Repo](https://github.com/watermelon588/Tripverse)

`LangGraph` · `FastAPI` · `PostgreSQL` · `SQLAlchemy` · `asyncpg` · `Groq` · `Gemini`

### 🔭 [SkyGuide AI](https://skyguide-ai.vercel.app) — distributed realtime system

Three services: React, an Express 5 gateway and a private FastAPI astronomy engine behind an allowlisted proxy. It scores 13,311 deep-sky objects in one vectorised pass for your exact telescope and sky, and guides the scope live over a 20 Hz WebSocket stream with a hysteresis lock state machine. Expensive responses come from a stale-while-revalidate cache with single-flight. [Repo](https://github.com/watermelon588/skyguide-ai)

`Microservices` · `FastAPI` · `Express 5` · `Socket.IO` · `Astropy` · `MongoDB`

### 🧠 [Neuron](https://github.com/watermelon588/Neuron) — multimodal retrieval & RAG

Text, image and audio fused into one CLIP query vector and re-ranked by a weighted blend of BM25, dense and visual similarity. Location-aware RAG cites the exact page and line, and the backend degrades gracefully: lazy models, then BM25, then extractive answers.

`FastAPI` · `CLIP` · `Whisper` · `FAISS` · `BM25` · `MongoDB`

### 🎙️ [KOE (声)](https://koe-pi.vercel.app/) — voice agent & connected workspace

A voice-first workday companion built on Gemini Live, web chat, and voice notes over a shared Python tool registry. Calendar, Google Docs/Sheets, GitHub and Notion workflows pass through a PostgreSQL-backed persisted approval gate: arguments freeze into a proposal with a 10-minute expiry, and an atomic claim stops duplicate clicks or race conditions before invoking allowlisted writers. AudioWorklet captures 16 kHz PCM16, scheduled 24 kHz Web Audio flushes immediately on user interruption, and an exclusive audio coordinator halts microphone acquisition if Spotify playback state is ambiguous. [Repo](https://github.com/watermelon588/Koe)

`FastAPI` · `Gemini Live` · `PostgreSQL (Neon)` · `AudioWorklet` · `WebSockets` · `Three.js (VRM)` · `React 19` · `TypeScript` · `OAuth`

### 🔖 [Shiori](https://github.com/watermelon588/Shiori-) — Go server hardening

I security-audited a Go/Echo media server (~300 routes) and closed a critical unauthenticated network exposure. I added a per-IP rate limiter, lockout, constant-time token checks and a strict CSP, then built sandboxed JavaScript providers (Goja) with automatic failover on top. **23/23 attack probes pass.**

`Go` · `Echo` · `GORM` · `SQLite` · `Goja` · `WebSockets`

### 💬 [Yap Chat](https://yap-chat-five.vercel.app) — realtime messaging & WebRTC

Room-scoped realtime chat and 8-way peer-to-peer video. Socket identity is verified from a JWT, and the WebRTC mesh is glare-free and never routes media through the server. **35/35 tests** pass against a live server. [Repo](https://github.com/watermelon588/Yap-Chat)

`Node.js` · `Socket.IO` · `WebRTC` · `MongoDB` · `JWT`

### 🌐 [Portfolio](https://portfolio-web-six-psi-43.vercel.app/) — five themes, one codebase

A quiet, text-led portfolio rendered across five distinct aesthetic variants (Paper, Ledger, Signal, Blueprint, Dial). Features an interactive 3D dice-roll preloader, procedural low-fi canvas veil filters (haze, mosaic, dither, smear, scribble), zero framework bloat, and smooth physics-driven kinetic scrolling. [Repo](https://github.com/watermelon588/portfolio-job)

`Vanilla JS` · `Vite` · `GSAP` · `Lenis` · `HTML5 / CSS3`

---

## Currently Going Deep On (現在の章)

| Area | What that looks like |
| --- | --- |
| **Agent harnesses** | The runtime around a model: step budgets, interrupts, tool gates and safe stops enforced in code |
| **Sandboxes** | Running agent actions and untrusted code with least privilege across browser, process and network boundaries |
| **Agent memory** | Checkpointed state, short- and long-term memory, what an agent should recall across sessions |
| **Retrieval pipelines** | Hybrid search, chunking that preserves citations, deciding what reaches the model and at what cost |
| **Evals & observability** | LangSmith traces, adversarial fixtures, regression suites: proof an agent works, not a demo |
| **Distributed systems** | Queues, idempotency, circuit breakers and caches that keep AI features up when providers aren't |

I took the long road to LLMs — NumPy, Pandas and scikit-learn, classical ML, deep learning, then transformers and modern GPT architectures — and I'm still working through the maths underneath: linear algebra, probability, optimisation. Models aren't black boxes if you know what's inside.

---

## Tech Stack (技術スタック)

[![My Skills](https://skillicons.dev/icons?i=python,fastapi,nodejs,express,postgres,mongodb,mysql,redis,supabase,docker,jenkins,linux,git,github,go,java,c,cpp,ts,js,react,sklearn,tailwind,figma&perline=12)](https://skillicons.dev)

- **AI & Agents:** LangGraph · LangChain · LangSmith · Gemini Live · MCP · RAG · AudioWorklet / Web Audio · Tool Calling · Embeddings · FAISS · Evals
- **Backend & Realtime:** FastAPI · Node.js · Express 5 · WebSockets · Socket.IO · WebRTC · REST APIs · Pydantic · Asyncio
- **Distributed Systems:** Microservices · API Gateways · Stale-While-Revalidate Caching · Rate Limiting · Job Queues (`SKIP LOCKED`) · Circuit Breakers · Sharding & Partitioning
- **Data & Storage:** PostgreSQL · MongoDB Atlas · MySQL · Redis · SQLite · Supabase (RLS) · GORM · SQLAlchemy / asyncpg
- **Security & Reliability:** JWT & HttpOnly Sessions · OWASP Top 10 · SSRF / CSRF Defense · Constant-time Crypto · Sandboxed Runtimes (Goja) · Threat Modeling
- **Testing & Tooling:** Docker · Linux · Jenkins CI · Git / GitHub · pytest · Vitest · LangSmith Regression Suites


---

## Recognition (実績)

* **Smart India Hackathon 2025** — National Finalist (backend for LivestockIQ)
* **SBI Ideathon 2025** — Top 1000 nationally (technical lead, PraanaCare)

## Writing (執筆)

* [Why does JavaScript feel so absurd? — Part 1](https://zaxx-blog.hashnode.dev/why-does-javascript-feel-so-absurd-part-1): type coercion & IEEE 754
* [Why does JavaScript feel so absurd? — Part 2](https://zaxx-blog.hashnode.dev/why-does-javascript-feel-so-absurd-part-2): functions, scope & composition
* [Why does JavaScript feel so absurd? — Part 3](https://zaxx-blog.hashnode.dev/why-does-javascript-feel-so-absurd-part-3): closures, the TDZ & `this`

---

## What I'm Building Toward

The goal isn't just to build applications **with** AI.

It's to build the systems **around** AI — and make them hold up:

**Models → Tools → Agents → Memory → Orchestration → Evals → Production**

That's the rabbit hole I'm currently in.

## Stats (記録)

[![Followers](https://img.shields.io/github/followers/watermelon588?style=flat-square&color=0D1117&labelColor=0D1117&logo=github&logoColor=FFFFFF&label=followers)](https://github.com/watermelon588?tab=followers)
[![Stars](https://img.shields.io/github/stars/watermelon588?style=flat-square&affiliations=OWNER&color=0D1117&labelColor=0D1117&logo=github&logoColor=FFFFFF&label=stars)](https://github.com/watermelon588?tab=repositories)
![Profile views](https://komarev.com/ghpvc/?username=watermelon588&style=flat-square&color=0D1117&label=profile+views)

<p align="center">
  <img src="https://streak-stats.demolab.com?user=watermelon588&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=watermelon588&theme=github-dark&hide_border=true&area=true&custom_title=Contribution%20activity&height=280" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=watermelon588&theme=github-compact&hide_border=true&area=true&custom_title=Contribution%20activity&height=280" width="100%" alt="Contribution activity graph" />
</picture>

---

## Links (繋がり)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/maity-rohit)
[![X](https://img.shields.io/badge/X-0D1117?style=flat-square&logo=x&logoColor=FFFFFF)](https://x.com/turquoise_0904)
[![Email](https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:maityrohit021@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-0D1117?style=flat-square&logo=instagram&logoColor=E4405F)](https://instagram.com/rohit_0.0)

---

<p align="center">
  心臓を捧げよ<br/>
  <i>Shinzou wo Sasageyo</i>
</p>
