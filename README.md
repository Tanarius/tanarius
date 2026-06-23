# Trey — AI / Agent Engineer

**I build autonomous agent systems — and the infrastructure that keeps them running in production.**

I'm an infrastructure engineer who went deep on AI and didn't come back. My background is the unglamorous half of the stack — routing, reliability, auth, cost, observability — which turns out to be exactly where agent and LLM systems actually break. I bring that discipline to building AI.

The throughline in how I think: an autonomous agent is a worker, orchestration is the org chart, model routing is dispatch, and the payment layer is the treasury. Most of the hard problems in agent systems aren't model problems — they're systems problems. That's the half I already come from.

---

### 🚀 What I've built

**[Simmer](https://simmer.kitchen)** — a household-first meal-planning app, live in early access.
React/Vite/TypeScript · Express 5 · Drizzle ORM · PostgreSQL (Neon) · Anthropic API. The architecture spine is household isolation (all data scoped to a `householdId`, enforced at the data layer with regression tests), with a two-tier model setup — a lightweight model for high-volume extraction, a stronger one for the conversational copilot.
→ [github.com/Tanarius/simmer](https://github.com/Tanarius/simmer)

**Spotter** — an AI agent I designed for Telegram (Python + Anthropic SDK): a single-user assistant that externalizes executive function through tool-driven task capture, next-action surfacing, and stall detection. Fully architected — agent loop with the model as router, an 8-tool schema, layered SQLite memory, and a documented path to multi-tenant scale.

---

### 🛠️ Working with

**Agents & AI:** Anthropic & OpenAI APIs · agent architecture & tool-calling · MCP · RAG (Pinecone, MongoDB Atlas)
**Languages:** Python · TypeScript · Node.js
**Frontend:** React · Vite · Next.js · Tailwind
**Backend & data:** Express · Drizzle ORM · PostgreSQL / Neon
**Infra:** AWS · Railway · Render · Docker

---

### ⚙️ How I work

I build through an agentic development workflow — and I treat it as an engineering discipline, not a shortcut.

In practice it's a three-layer system: I direct product and architecture, a reasoning model acts as my architectural partner, and an agent-first IDE handles execution. I own the decisions that matter — what to build, how it's structured, which tradeoffs to make — and I delegate the typing, not the thinking.

What keeps it production-grade is the rigor around it: read-only investigation before any edit, type-checks and tests after every change, work isolated on branches, reviewed via pull request, auto-deployed, then verified live. The instincts I built doing infrastructure — assume nothing, verify everything, isolate the blast radius — are what keep an AI-accelerated workflow rigorous instead of reckless.

The result: I move at the speed of agentic tooling while holding the bar of someone who's run production systems. That's the direction the whole field is heading, and it's already how I build.

---

### 📫 Reach me

- 🌐 Live project: [simmer.kitchen](https://simmer.kitchen)
- 💼 LinkedIn: `(https://www.linkedin.com/in/treytenellingson/)`
- 📧 `tanariustrey@gmail.com`

---

*Focused on AI / agent engineering roles — building production agent systems with an infrastructure edge.*
