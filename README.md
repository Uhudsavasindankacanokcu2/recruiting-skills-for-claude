# Recruiting & HR Skills for Claude 🧑‍💼

**Turn Claude into a recruiting coordinator.** A pack of [Claude Skills](https://docs.claude.com/en/docs/claude-code/skills) that write job descriptions, screen resumes, and build structured interviews — fast, consistent, and bias-aware.

For founders, recruiters, agencies, and hiring managers who do the hiring grind without a full HR team.

---

## ✨ What's inside (free core)

| Skill | What it does |
|-------|--------------|
| **job-description-writer** | Role brief → conversion-optimized, inclusive JD with must-have/nice-to-have split, salary-band guidance, and a screening scorecard. Trims inflated requirements that scare off good candidates. |
| **resume-screener** | Resumes + JD → objective fit score with **quoted evidence**, gaps turned into screening questions, ranked shortlist — with **bias actively suppressed** (ignores name/age/gender/school). |
| **interview-kit-builder** | Role → competency map, behavioral questions, **what good vs weak answers look like**, a 1–4 scoring rubric, and a stage plan. Structured interviews that actually predict performance. |

Each skill is a single `SKILL.md` — drop it in `~/.claude/skills/` and Claude uses it automatically.

---

## 🚀 Quick start
1. Copy a skill folder into `~/.claude/skills/`.
2. Ask Claude: *"Write a JD for a senior backend engineer, remote, then build me an interview kit."*
3. Get a hiring-ready output.

---


---

## 👀 See it in action

**You paste a resume + the role**, and ask Claude to screen it:

```
Role: Senior Backend Engineer (must-haves: 5+ yrs backend, Go or Java,
distributed systems, SQL; nice-to-have: Kubernetes, fintech)

Resume: Alex M. — 6 yrs backend. Built payment processing at a fintech
startup (Go, PostgreSQL, gRPC microservices on AWS). Led migration to
event-driven architecture handling 10k req/s. No Kubernetes mentioned.
```

**Claude returns** (resume-screener skill, bias-suppressed):

---

**Fit score: 8.5/10 — Advance.** Strong evidence on every must-have; one nice-to-have unverified.

| Requirement | Met? | Evidence (quoted) |
|-------------|------|-------------------|
| 5+ yrs backend | ✅ Met | "6 yrs backend" |
| Go or Java | ✅ Met | "Go, PostgreSQL, gRPC" |
| Distributed systems | ✅ Met | "event-driven architecture handling 10k req/s", "gRPC microservices" |
| SQL | ✅ Met | "PostgreSQL" |
| Kubernetes (nice) | ⚠️ Not shown | Not mentioned — **ask**, don't assume absent |
| Fintech (nice) | ✅ Met | "payment processing at a fintech startup" |

**Strengths:** Direct payments/fintech experience, real scale (10k req/s), led an architecture migration (seniority signal), exact tech-stack match.

**Gaps → screening questions (not assumptions):**
- "Have you worked with Kubernetes or another orchestration platform? At what depth?"
- "Walk me through the 10k req/s migration — what broke, what you'd do differently."

**Verdict:** Advance to technical interview. Must-haves fully evidenced; the only gap (K8s) is a nice-to-have and a question, not a disqualifier.

*Evaluated on skills and evidence only — name, age, gender, and school were ignored. Final hiring decisions and EEO compliance rest with your team.*

---

> The skill **quoted evidence** for every rating, turned the gap into a question instead of a rejection, and ignored everything not job-related.

---

## 💎 Pro pack — 6 skills

**[Recruiting Skills Pro →](GUMROAD_LINK_HERE)** adds:
- **outreach-writer** — personalized candidate outreach that gets replies (not spammy templates)
- **offer-letter-builder** — clean offer letters + comp-package explainer for candidates
- **candidate-feedback-writer** — fair, legally-careful rejection/feedback messages at scale
- Priority updates + new skills

**One-time payment. No subscription.** [Get the Pro pack →](GUMROAD_LINK_HERE)

---

## Why bias-aware matters
Hiring is legally sensitive. These skills evaluate on **job-related evidence only**, flag illegal/inadvisable interview questions, and keep your process consistent and defensible. They support — they don't replace — human hiring decisions and HR/legal review for your jurisdiction.

---
⭐ **Star this repo** if it saved you a hiring headache. New free skills added regularly.

*Made for the Claude Skills ecosystem.*

## 🔗 More Claude Skill Packs

- 💸 [Finance Skills](https://github.com/Uhudsavasindankacanokcu2/finance-skills-for-claude) — cash flow, runway, invoices, budgets, pricing
- ⚖️ [Legal Skills](https://github.com/Uhudsavasindankacanokcu2/legal-skills-for-claude) — contract review, drafting, negotiation
- 🛒 [E-commerce Seller Skills](https://github.com/Uhudsavasindankacanokcu2/ecommerce-skills-for-claude) — listings, reviews, ad spend
