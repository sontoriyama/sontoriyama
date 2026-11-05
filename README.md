# Pol Figuerola (`@sontoriyama`) 👋

### Full-Stack & Security Engineer · Open-Source Contributor
**High-Performance Browser Architectures, AI Agents (MCP) & Real-Time Audio Streaming**

🚀 **From a passionate self-taught developer to a contributor in major AI ecosystems.**  
Over the past 4+ years, I have evolved from full-stack web engineering into low-latency browser systems, edge runtimes, and multi-layered security architectures—focusing on making real-time AI interactions feel instantaneous.

---

### 🔭 Flagship Project: [Vozflow](https://vozflow.dev) *(Chrome Manifest V3 & Bun)*

I am the creator of **[Vozflow](https://vozflow.dev)**, a next-generation Chrome MV3 extension and cloud platform integrating real-time **ASR (Automatic Speech Recognition)**, **Neural TTS (Text-to-Speech)**, and **Context-Aware AI Refinement** directly into any web workflow.

* **Zero-Copy Audio Pipeline:** Engineered with custom `AudioWorklet` processors, dedicated OPFS workers, and `Transferable` memory buffers (`O(1)` RAM overhead) to stream audio seamlessly without touching disk or blocking the V8 Garbage Collector.
* **Ultra-Low-Latency Runtime:** Powered by **Bun** and **Elysia** microservices with sticky-session cluster routing on Fly.io and real-time NDJSON/WebSocket audio streaming.
* **Resilient MV3 Architecture:** Deterministic Offscreen document lifecycle management, Single-Actor Storage (SSOT), closed Shadow DOM isolation, and transactional credit ledgers backed by PostgreSQL, Valkey/Redis, Clerk, and Stripe.

---

### 🏆 Big Tech Open-Source Contribution: Alibaba Cloud (`@QwenLM`)

Official contributor to the **QwenLM** ecosystem, one of the most powerful open-weight LLM families in the world.

* **The Context:** Contributed to [`QwenLM/qwen-code`](https://github.com/QwenLM/qwen-code) (Qwen-Agent CLI), architecturally inspired by Google's `gemini-cli`.
* **The Contribution:** Authored comprehensive integration logic, configuration specifications, and execution guides for the **Model Context Protocol (MCP)**—bridging gaps in agent tool instructions.

🔗 **[See my accepted Pull Request: Model Context Protocol (MCP) Integration (#796)](https://github.com/QwenLM/qwen-code/pull/796)**

---

### 🛠 Tech Stack & Engineering Arsenal

I don't limit myself to a single framework; I choose the runtime and protocol that make the code fly.

* **Core & Runtimes:** TypeScript (Strict ESM), JavaScript (ESNext), **Bun**, Node.js
* **Browser & Frontend:** Chrome Extensions (**Manifest V3**, Service Workers, Offscreen API, OPFS, Web Audio API), React 19, Next.js, Astro, Vite, Tailwind CSS
* **Backend & Streaming:** **Bun**, Elysia, Hono, Native WebSockets, NDJSON Streaming, tRPC, Express
* **AI & Multimodal Protocols:** Google Gemini API, QwenLM, **MCP (Model Context Protocol)**, Whisper (ASR), Neural TTS Pipelines, WebGL/Three.js audio visualizations
* **Data, Security & Infrastructure:** PostgreSQL, Redis / Valkey, Docker, Fly.io, Clerk, Stripe, Runtime Security Hardening

---

### 📜 My Story & Philosophy

I started over 4 years ago studying day and night (kudos to the community: Midu, Fazt) with a focus on *Mobile First* and extreme performance optimization. Today, I design real-time audio streaming systems, harden production runtimes, and collaborate on the codebases of global AI models.

> *"I don't just want it to work, I want it to fly. If I have to go down to the level of ArrayBuffers, streams, and runtime internals to optimize, that's where you'll find me."*

---

### 📫 Connect with Me

I am open to collaborations on **Open Source projects**, **AI Agent & MCP integrations**, **Application Security**, or complex web architecture challenges.

* 🌐 **Product:** [https://vozflow.dev](https://vozflow.dev)
* 📧 **Email:** [songokumbl@gmail.com](mailto:songokumbl@gmail.com)
* 💻 **GitHub:** [sontoriyama](https://github.com/sontoriyama)
