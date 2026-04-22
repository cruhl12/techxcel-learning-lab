# Capstone Project: Meridian Legal AI

**Target completion:** 16 June 2026
**Demo date:** Week 9 rehearsal, Week of 17 June 2026

---

## What This Is

A full demonstration of the TechXcel product stack applied to a fictional law firm: **Meridian Legal** (a 45-person Perth commercial law firm). This is the artifact you show TechXcel to prove you're ready for the Agentic Solutions Officer role.

It is not a toy. It is not a tutorial project. It should look and feel like something TechXcel could actually deliver to a client.

---

## The Four Deliverables

### 1. Working AI Platform
A functional AI chat interface backed by the Anthropic API with a Company Knowledge Base (RAG).

**Technical requirements:**
- Python-based backend calling the Anthropic API
- RAG pipeline ingesting at least 5 fictional Meridian Legal documents (e.g. staff handbook, billing policy, client intake procedure, email templates, FAQ)
- Multi-model support — ability to switch between Anthropic Claude and OpenAI GPT backend with a config change
- Responses are grounded in the Meridian documents, not just general AI knowledge

**What it must be able to do:**
- Answer questions about Meridian Legal's policies using the knowledge base
- Demonstrate the difference between a response with and without the knowledge base
- Switch models and show the difference in output

### 2. Client Proposal
A TechXcel-standard proposal for Meridian Legal — same structure as the actual TechXcel proposal, populated with Meridian-specific content.

**Requirements:**
- Uses the TechXcel proposal as the structural template
- Pricing left as bracketed placeholders (you don't have real pricing)
- Risk Profile section filled out for a law firm (data sensitivity is high — Secure profile default)
- Competitive positioning included
- Calm Authority brand tone throughout
- No student-project language — could be handed to a CFO

### 3. AI Launch Program — Week 3 Training Materials
A prompt cheat sheet and quick-start guide for Meridian Legal staff — as if you were the one delivering the AI Launch Program.

**Requirements:**
- Prompt cheat sheet: 10 example prompts relevant to legal work (drafting, research, summarising, client comms)
- Quick-start guide: 1-page, plain English, tells a non-technical lawyer how to get started with Meridian Legal AI
- TechXcel brand tone throughout

### 4. SKILL.md — "Deploy [Client] AI for a New Client"
A SKILL.md file encoding the end-to-end process of deploying the TechXcel platform for a new client — from signed agreement to go-live.

**Requirements:**
- Follows the `skills/_template.md` format
- Detailed enough that another person could follow it
- Includes the Risk Profile decision tree
- References the AI Launch Program structure

---

## The 10-Minute Demo

**Audience:** Non-technical executive (imagine Meridian Legal's Managing Partner)

**Structure:**
1. (2 min) The problem — "Here's what happens when your team uses personal AI accounts"
2. (3 min) The platform demo — show a live conversation with Meridian Legal AI, using the knowledge base
3. (2 min) The difference — show the same question answered without the knowledge base vs. with it
4. (2 min) What this means for Meridian — governance, compliance, productivity
5. (1 min) What's next — the AI Launch Program

**Rules for the demo:**
- No "let me just..." or "ignore that error" — it must work cleanly
- No jargon the audience wouldn't know — if you say "RAG", you've failed
- Prepare for the question: "How is this different from ChatGPT?" — have a clean 30-second answer

---

## Fictional Client Profile — Meridian Legal

Use this when creating documents and demo content.

- **Name:** Meridian Legal
- **Type:** Commercial law firm, Perth WA
- **Size:** 45 staff (30 lawyers, 10 admin, 5 leadership)
- **Industry:** Legal — high data sensitivity, client confidentiality obligations
- **AI maturity:** Low — some staff use ChatGPT personally, leadership concerned about data risk
- **Primary concern:** Confidential client data leaving Australia
- **Secondary concern:** Inconsistent AI use creating compliance exposure
- **Decision-maker:** Sarah Okoro, Managing Partner

---

## Suggested Fictional Documents to Create

Use these as knowledge base source documents. Keep them short (1–2 pages each) and realistic.

1. `meridian-staff-handbook-excerpt.txt` — sections on client confidentiality, data handling policy
2. `meridian-billing-policy.txt` — fee structures, billing increments, invoice terms
3. `meridian-client-intake-procedure.txt` — how new client matters are opened
4. `meridian-email-templates.txt` — 5 standard email templates (client update, invoice, matter close)
5. `meridian-faq-for-staff.txt` — 10 common internal questions about firm policies

---

## Success Criteria

The capstone is done when you can answer yes to all of these:

- [ ] The demo runs end-to-end without errors
- [ ] A non-technical person watching would understand what the product does and why it matters
- [ ] The proposal could be handed to a CFO without embarrassment
- [ ] The training materials are specific to Meridian Legal, not generic AI content
- [ ] The SKILL.md is detailed enough that someone else could follow it
- [ ] Everything is committed to GitHub with clean, professional commit history
