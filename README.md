# Pol Figuerola (`@sontoriyama`) 👋

### Full-Stack & Security Engineer · Open-Source Contributor
**High-Performance Browser Architectures, AI Agents (MCP) & Real-Time Audio Streaming**

🚀 **From a passionate self-taught developer to an upstream contributor at Microsoft, Pydantic, StablyAI, and Alibaba Cloud (`@QwenLM`).**  
Over the past 4+ years, I have evolved from full-stack web engineering into low-latency browser systems, edge runtimes, and multi-layered security architectures—focusing on making real-time AI interactions feel instantaneous.

---

### 🔭 Flagship Project: [Vozflow](https://vozflow.dev) *(Chrome Manifest V3 & Bun)*

I am the creator of **[Vozflow](https://vozflow.dev)**, a next-generation Chrome MV3 extension and cloud platform integrating real-time **ASR (Automatic Speech Recognition)**, **Neural TTS (Text-to-Speech)**, and **Context-Aware AI Refinement** directly into any web workflow.

* **Zero-Copy Audio Pipeline:** Engineered with custom `AudioWorklet` processors, dedicated OPFS workers, and `Transferable` memory buffers (`O(1)` RAM overhead) to stream audio seamlessly without touching disk or blocking the V8 Garbage Collector.
* **Ultra-Low-Latency Runtime:** Powered by **Bun** and **Elysia** microservices with sticky-session cluster routing on Fly.io and real-time NDJSON/WebSocket audio streaming.
* **Resilient MV3 Architecture:** Deterministic Offscreen document lifecycle management, Single-Actor Storage (SSOT), closed Shadow DOM isolation, and transactional credit ledgers backed by PostgreSQL, Valkey/Redis, Clerk, and Stripe.

---

### 🏆 Open-Source Contributions (Big Tech & AI Ecosystems)

Active upstream contributor to major developer tools, AI agent orchestrators, and open-weight LLM ecosystems:

* **Microsoft — [`microsoft/intelligent-terminal`](https://github.com/microsoft/intelligent-terminal)** *(Rust & Windows Shell Dispatch)*
  * **The Fix:** Diagnosed and eliminated JSON quoting/escaping corruption in `wt-agent-hooks` (`PreToolUse`) across Windows `cmd`/PowerShell dispatch using quote-free serialization, restoring deterministic agent tool permissions and adding Rust regression test coverage.
  * 🔗 **[Merged PR #1407: `fix(wta): avoid escaped quotes in Antigravity PreToolUse hook command`](https://github.com/microsoft/intelligent-terminal/pull/1407)** *(Fixes #1406)*

* **Pydantic — [`pydantic/pydantic-ai`](https://github.com/pydantic/pydantic-ai)** *(Python & AI Agent Framework)*
  * **The Fix:** Verified OpenAI Chat Completions behavior across GPT-5.4, GPT-5.5, and GPT-5.6 variants via live API probes and wired `OpenAIProvider` / `OpenAIChatModel` to raise `ModelRequestRejectedError` pre-flight when function tools are combined with reasoning on affected models—preventing avoidable runtime HTTP 400 failures while preserving working defaults, backed by matrix tests and recorded cassettes.
  * 🔗 **[Merged PR #14887: `Raise ModelRequestRejectedError before OpenAIChatModel sends tools to GPT-5.4 and GPT-5.6 models with reasoning on`](https://github.com/pydantic/pydantic-ai/pull/14887)** *(Closes #13512; builds on #14369)*

* **StablyAI — [`stablyai/orca`](https://github.com/stablyai/orca)** *(TypeScript & AI Agent Orchestration)*
  * **The Fix:** Fixed Antigravity session resume launch recipes so the resolved `--model` flag is cleanly replayed on conversation follow-ups, preventing empty-model runtime failures while composing cleanly with upstream launch changes.
  * 🔗 **[Merged PR #43217: `fix(antigravity): replay only resolved --model in resume launch recipe`](https://github.com/stablyai/orca/pull/43217)** *(Fixes #43154)*

* **Alibaba Cloud — [`QwenLM/qwen-code`](https://github.com/QwenLM/qwen-code)** *(Model Context Protocol & Agent CLI)*
  * **The Contribution:** Authored integration logic, configuration specifications, and execution guides for the **Model Context Protocol (MCP)** in the Qwen-Agent CLI, bridging critical gaps in agent tool instructions.
  * 🔗 **[Merged PR #796: Model Context Protocol (MCP) Integration](https://github.com/QwenLM/qwen-code/pull/796)**

---

### 🛠 Tech Stack & Engineering Arsenal

I don't limit myself to a single framework; I choose the runtime and protocol that make the code fly.

* **Core & Runtimes:** TypeScript (Strict ESM), JavaScript (ESNext), **Python**, **Rust**, **Bun**, Node.js
* **Browser & Frontend:** Chrome Extensions (**Manifest V3**, Service Workers, Offscreen API, OPFS, Web Audio API), React 19, Next.js, Astro, Vite, Tailwind CSS
* **Backend & Streaming:** **Bun**, Elysia, Hono, Native WebSockets, NDJSON Streaming, tRPC, Express
* **AI & Multimodal Protocols:** Google Gemini API, QwenLM, **MCP (Model Context Protocol)**, AI Agent Tooling & Hooks, Whisper (ASR), Neural TTS Pipelines, WebGL/Three.js audio visualizations
* **Data, Security & Infrastructure:** PostgreSQL, Redis / Valkey, Docker, Fly.io, Clerk, Stripe, Runtime Security Hardening

---

### 📜 My Story & Philosophy

I started over 4 years ago studying day and night (kudos to the community: Midu, Fazt) with a focus on *Mobile First* and extreme performance optimization. Today, I design real-time audio streaming systems, harden production runtimes, and contribute upstream to global developer tools and AI ecosystems.

> *"I don't just want it to work, I want it to fly. If I have to go down to the level of ArrayBuffers, streams, and runtime internals to optimize, that's where you'll find me."*

---

### 📫 Connect with Me

I am open to collaborations on **Open Source projects**, **AI Agent & MCP integrations**, **Application Security**, or complex web architecture challenges.

* 🌐 **Product:** [https://vozflow.dev](https://vozflow.dev)
* 📧 **Email:** [songokumbl@gmail.com](mailto:songokumbl@gmail.com)
* 💻 **GitHub:** [sontoriyama](https://github.com/sontoriyama)
