# Mahesh Singh

**Software Engineer — Distributed Systems & Infrastructure**  
Ludhiana, India &middot; [LinkedIn](https://www.linkedin.com/in/maheshsingh20) &middot; [Codeforces](https://codeforces.com/profile/maheshsingh0905a) &middot; [Email](mailto:singhmahesh2924@gmail.com)

---

I engineer high-throughput backend services, resilient distributed queue architectures, and developer tooling for agentic AI systems. My work focuses on concurrency control, deterministic testing of asynchronous systems, and protocol instrumentation for autonomous agents.

- **Systems & Concurrency:** Deep experience with Redis internals, atomic Lua scripts for stalled-job recovery, and distributed worker orchestration (BullMQ).
- **Agentic Infrastructure:** Core contributor to Model Context Protocol (MCP) tooling, including Chrome DevTools MCP runtime instrumentation and multi-agent coordination frameworks.
- **Problem Solving:** Active competitive programmer on [Codeforces](https://codeforces.com/profile/maheshsingh0905a) with a focus on graph algorithms, dynamic programming, and computational complexity.

---

### Selected Engineering & Open Source

#### [Chrome DevTools MCP](https://github.com/maheshsingh20/chrome-devtools-mcp) &middot; `TypeScript` `Chrome DevTools Protocol` `MCP` `Sinon`
*Chrome DevTools bridge enabling autonomous AI coding agents to inspect, snapshot, and debug browser runtime state.*
- Architected Sinon mock factories (`createHandlerMocks`, `createMockPuppeteerPage`) across emulation, screencast, and snapshot tools, eliminating real browser launches in CI and significantly accelerating test feedback loops.
- Implemented unit coverage for `McpPage` CDP session handling, offline throttling, and secondary DevTools session delegation.
- Contributed core refactors merged upstream (#2641, #2665, #2683).

#### [Distributed Queue Engineering — BullMQ & Redis](https://github.com/maheshsingh20) &middot; `Redis` `Lua` `BullMQ` `Distributed Systems`
*Zero-loss task processing and stall recovery under high concurrency and network partitions.*
- Investigated and authored atomic Lua patches (`moveStalledJobsToWait`, `moveToActive`) to eliminate edge-case race conditions where stalled jobs could be dropped or duplicated during worker crashes.
- Built reproducible high-concurrency stress test suites validating Redis lock renewals and deterministic recovery transitions.

#### [OpenMAIC](https://github.com/maheshsingh20/OpenMAIC) &middot; `Python` `Multi-Agent Systems` `LLM Orchestration`
*Open Multi-Agent Interactive Classroom for coordinated, multi-agent learning environments.*
- Designed multi-agent communication pipelines coordinating specialized agent roles into interactive instructional workflows.
- Structured agent state synchronizations and real-time response streams for low-latency feedback.

#### [Codeburn](https://github.com/maheshsingh20/codeburn) &middot; `Node.js` `CLI` `Telemetry`
*Local-first telemetry and cost-tracking engine for AI coding agents.*
- Track token usage, cost profiles, and model metrics across 37+ AI coding tools and CLI agents (Claude Code, Cursor, Codex, Gemini).

---

### Technical Focus

| Domain | Technologies & Primitives |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (Node.js), Go, Python, C++, C#, Lua, SQL |
| **Distributed Systems & Queues** | Redis (Lua scripting, Pub/Sub, Streams, Locks), BullMQ, Asynchronous Event Loops, Fault-Tolerant Job Scheduling |
| **Protocols & Agent Tooling** | Model Context Protocol (MCP), Chrome DevTools Protocol (CDP), Puppeteer, REST, gRPC, WebSockets |
| **Data & Storage** | PostgreSQL, Redis, MongoDB, MySQL |
| **Engineering Practices** | Deterministic asynchronous testing (Sinon, Vitest, Jest), Docker, Linux, GitHub Actions CI/CD |

---

### Recent Contributions

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---

### Availability

Open to backend engineering and distributed systems roles where mission-critical infrastructure, high concurrency, and systems reliability are the primary focus.

Reach out via [LinkedIn](https://www.linkedin.com/in/maheshsingh20) or [singhmahesh2924@gmail.com](mailto:singhmahesh2924@gmail.com).
