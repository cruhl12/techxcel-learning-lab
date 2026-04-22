# Exercise 01 — Prompt Anatomy

## The Five Components
| Component | Purpose |
|-----------|---------|
| Role | Who the AI is — shapes tone, expertise, perspective |
| Context | The situation — what the AI needs to know |
| Task | The specific thing to produce — precise, not vague |
| Format | How the output should be structured |
| Constraints | What to avoid, limits, rules |

---

## Final Prompt

You are the senior client manager at TechXcel, writing a follow-up email on behalf of the team for a client that had their kickoff session today. The client is a 60-person accounting firm. They left the session positive about the product but have concerns about data leaking outside of Australia. Your goal is to reassure their confidence and move them toward proceeding with Week 2. All TechXcel AI products are hosted on secure Azure data centres in Australia. Use a Calm Authority, Trusted, Quiet Competence voice. Write the full email including subject line. 3–4 short paragraphs. No bullet points. No headers.

---

## Output

**Subject:** Your data stays in Australia

Your data stays in Australia. You own it, you control it — here is how.

Every prompt your staff sends, every document they upload, and every response they receive stays within Australia. Your platform runs on Microsoft Azure's Australian data centres — infrastructure that holds your data in-region by design, not by configuration. It does not leave. That is not a setting that can be accidentally changed. It is the architecture.

Accounting firms carry a particular responsibility around client confidentiality. We built the platform with that in mind. Your data is yours, housed in infrastructure you own, in the country you operate in.

We are ready to move into Week 2 when you are. We will be in touch shortly to confirm timing for the platform deployment and your Champion session. If any questions come up before then, reply here and we will get back to you the same day.

[Your name]
Senior Client Manager
TechXcel

---

## What I Learned

- A prompt without Format produces unpredictable output — always specify length and structure
- "Lead with the answer" means the first sentence should be the point, not a warm-up
- Precise terminology (e.g. "Champion session") is not a filler phrase — filler phrases are marketing noise with no specific meaning
- Declarative statements ("Your data stays in Australia") are stronger than gerunds ("Keeping your data safe") — state the fact, don't describe the action
- Every word in a subject line must earn its place — a generic subject line is an unopened email
