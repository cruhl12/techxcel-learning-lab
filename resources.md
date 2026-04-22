# Resource Index

Curated external learning by topic. Start with the linked official docs — they're more reliable than tutorials. Use YouTube to fill conceptual gaps, not as a primary source.

---

## 01 — Git & GitHub

| Resource | Type | Why |
|----------|------|-----|
| https://docs.github.com/en/get-started | Official docs | Start here — GitHub's own getting started guide |
| https://git-scm.com/book/en/v2 | Book (free, online) | Pro Git — the definitive reference; Chapters 1–3 cover everything you need |
| https://docs.github.com/en/repositories | Official docs | How repos work — branching, commits, pull requests |

**What to search on YouTube:** "Git and GitHub for beginners" — look for videos under 30 minutes that cover: init, add, commit, push, pull, branches.

**What you need to be able to do:** Create a repo, commit changes, push to GitHub, create a branch, open a pull request. Nothing more at this stage.

---

## 02 — Prompt Engineering

| Resource | Type | Why |
|----------|------|-----|
| https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview | Official docs | Anthropic's prompt engineering guide — primary reference |
| https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/prompt-library | Official docs | Real examples of structured prompts |
| https://learnprompting.org | Free course | Good structured introduction; skip anything that feels like padding |

**What to search on YouTube:** "Prompt engineering for business" — look for examples applied to real business tasks, not toy demos.

**What you need to be able to do:** Write a prompt with clear role, context, task, format, and constraints. Critique your own prompts before running them.

---

## 03 — API Integration

| Resource | Type | Why |
|----------|------|-----|
| https://docs.anthropic.com/en/api/getting-started | Official docs | Anthropic API — start here |
| https://docs.anthropic.com/en/docs/about-claude/models/overview | Official docs | Current Claude models and when to use each |
| https://platform.openai.com/docs/overview | Official docs | OpenAI API — the other primary provider TechXcel uses |
| https://platform.openai.com/docs/models | Official docs | OpenAI model reference |

**What to search on YouTube:** "Anthropic Claude API Python tutorial" — look for recent videos (2025+) showing basic API calls.

**What you need to be able to do:** Make a working API call to both Anthropic and OpenAI. Understand tokens, pricing, rate limits, model selection.

---

## 04 — Azure Fundamentals

| Resource | Type | Why |
|----------|------|-----|
| https://learn.microsoft.com/en-us/azure/fundamentals | Official docs | Azure fundamentals — start here for concepts |
| https://learn.microsoft.com/en-us/azure/ai-services/openai/overview | Official docs | Azure OpenAI Service — how TechXcel's platform runs |
| https://learn.microsoft.com/en-us/azure/architecture/ai-ml | Official docs | Azure AI architecture patterns |

**What to search on YouTube:** "Azure fundamentals for beginners 2025" — look for the AZ-900 exam prep content; it covers exactly what you need conceptually without going too deep.

**Certification to consider:** AZ-900 (Azure Fundamentals) — a 1-day study certification that signals Azure literacy to any client. Low bar, high signal for someone in this role.

**What you need to be able to do:** Explain what an Azure tenant is, how resource groups work, what Azure OpenAI Service is and how it differs from calling OpenAI directly. Enough to have an intelligent conversation with a client's IT team.

---

## 05 — RAG & Knowledge Bases

| Resource | Type | Why |
|----------|------|-----|
| https://docs.anthropic.com/en/docs/build-with-claude/embeddings | Official docs | Anthropic's guide to embeddings (core concept for RAG) |
| https://python.langchain.com/docs/tutorials/rag | Official docs | LangChain RAG tutorial — one of the most practical starting points |
| https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search | Official docs | Azure AI Search — how TechXcel's knowledge base likely runs in Azure |

**What to search on YouTube:** "RAG pipeline Python tutorial 2025" — look for videos that build it from scratch so you understand what's happening, not just copy-paste.

**What you need to be able to do:** Build a simple RAG pipeline that takes a document, chunks it, embeds it, stores it, and retrieves relevant chunks to answer a question. This is the Company Knowledge Base feature.

---

## 06 — Agentic Systems & Claude Code

| Resource | Type | Why |
|----------|------|-----|
| https://docs.anthropic.com/en/docs/claude-code/overview | Official docs | Claude Code — the primary tool for this role |
| https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview | Official docs | Tool use / function calling — foundation of agentic systems |
| https://docs.anthropic.com/en/docs/build-with-claude/agents | Official docs | Building agents with Claude |
| https://modelcontextprotocol.io/introduction | Official docs | MCP (Model Context Protocol) — how Claude Code connects to external systems |

**What you need to be able to do:** Build a multi-step agent that takes an input, uses tools, and produces a structured output. Understand what MCP is and what you can connect to it.

---

## 07 — SKILL.md Writing

No external resources needed. The template is in `skills/_template.md`. The skill is developed by writing them — start after completing a project, immediately encode what you learned.

**Reference:** Look at the SKILL.md files Claude Code uses internally for its own skills. The pattern is: purpose, inputs, steps, outputs, edge cases.

---

## 08 — Client Communication & Proposals

| Resource | Type | Why |
|----------|------|-----|
| TechXcel proposal (in this repo) | Reference | This IS the template. Study the structure, tone, and logic. |
| https://docs.anthropic.com/en/docs/about-claude | Official docs | Understanding what Claude can and can't do — essential for honest client conversations |

**What to search on YouTube:** "Executive AI presentation" — look for examples of AI capability being explained to non-technical leadership.

**What you need to be able to do:** Explain what RAG is, what an agentic workflow is, and what Azure data residency means — all in plain English, in under 2 minutes each, without losing accuracy.

---

## Competitive Landscape Reference

Quick reference for client conversations:

| Product | Price (est. 70 users) | Key weakness vs TechXcel |
|---------|----------------------|--------------------------|
| Microsoft Copilot | ~A$22,600/yr | Generic training, no adoption support, Microsoft-managed infra |
| ChatGPT Enterprise | ~A$30,000/yr | Data outside client tenant, no adoption support |
| DIY Azure build | A$50k–$150k+ setup | 3–6 months to build, no training, ongoing maintenance burden |
| TechXcel | Custom pricing | Client-owned infra, end-to-end delivery, model-agnostic |

---

## Personal Goal Alignment

**Cooper's goal:** Remote work 3–4 days/week, not confined to Perth, open to travel within Australia and internationally.

**Roles at TechXcel most likely to enable this:**
- **Premium Projects delivery** — agentic workflows are built remotely; client delivery can be done via Zoom
- **AI Launch Program facilitation** — training sessions can run remotely; in-person only for week 3 all-hands

**Skills that increase remote viability:** Strong async communication (written proposals, documentation), reliable independent delivery, minimal hand-holding needed from leadership.

**International pathway:** Singapore, UK, Netherlands are high-demand markets for enterprise AI consulting. The AZ-900 certification + demonstrated agentic build capability + client-facing portfolio positions you for that market.
