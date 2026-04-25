# Claude Code Skills — BDNHOST

> **Looking for the full registry?** Browse **250+ verified Claude Code skills**, auto-discovered daily across the ecosystem, at **[claude-skills.bdnhost.net](https://claude-skills.bdnhost.net/) →**

[![Registry](https://img.shields.io/badge/Registry-250%2B%20skills-FF4D00?style=flat-square)](https://claude-skills.bdnhost.net/)
[![Categories](https://img.shields.io/badge/Categories-15-0A0A0A?style=flat-square)](https://claude-skills.bdnhost.net/)
[![Auto-discovered](https://img.shields.io/badge/Auto--discovered-daily-0057FF?style=flat-square)](https://claude-skills.bdnhost.net/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Languages](https://img.shields.io/badge/Skills-EN%20%C2%B7%20HE%20%C2%B7%20ZH-D946EF?style=flat-square)](https://claude-skills.bdnhost.net/)

---

## What this repo is

This repository hosts the **public Claude Code skills authored by [BDNHOST](https://bdnhost.net/)** — production-grade skills extracted from real client work.

It is **one of nine sources** feeding the [Claude Code Skills Registry](https://claude-skills.bdnhost.net/), a curated discovery hub that aggregates verified `SKILL.md` files from:

- `anthropics/skills` (official)
- `obra/superpowers`
- `jeffallan/claude-skills`
- `akin-ozer/cc-devops-skills`
- `daymade/claude-code-skills`
- `bdnhost/claude-skills` ← **you are here**
- + automated daily discovery across GitHub

**👉 [Search 250+ skills with filters →](https://claude-skills.bdnhost.net/)**

---

## Why a registry, not just a list?

Most "claude-skills" repos and awesome-lists are static. The [registry](https://claude-skills.bdnhost.net/):

- ✅ **Auto-discovers** new skills daily (n8n workflow + GitHub code search)
- ✅ **Classifies** with hybrid LLM+keyword logic into 15 categories
- ✅ **Verifies** SKILL.md frontmatter (skips abandoned + non-skill repos)
- ✅ **Multilingual** — English, Hebrew, Chinese, with native search
- ✅ **Deep-linkable** — every skill has its own `/s/<id>/` URL with rich OG previews
- ✅ **No tracking, no signup wall, no ads**

[Read how it works →](https://claude-skills.bdnhost.net/#about)

---

## Skills in this repo

### ⭐ `lahav433` · Investigative Journalism Engine
FBI-grade OSINT + Intelligence Cycle methodology for autonomous newsrooms. Forensic accounting (Benford's Law, procurement compliance), pre-publication legal review, triple-source verification.
**Activates on:** "investigate", "audit tenders", "follow the money", OSINT, Intelligence Cycle.
**Category:** Specialized Domains · **Languages:** EN / HE · **Verified**

### 🏛️ `journalism-legal-il` · Israeli Press-Law Advisor
Standing legal advisor for Israeli news outlets. Covers defamation, privacy, FOIA, source protection. Produces safe-to-publish edited versions with change explanations.
**Activates on:** "is this defamation?", "can I publish this?", "received a lawyer letter", source protection.
**Category:** Specialized Domains · **Languages:** EN / HE · **Verified**

> ⚠️ Not a substitute for licensed legal counsel on high-stakes matters.

---

## Quick install

```bash
# Navigate to your Claude Code skills dir
mkdir -p ~/.claude/skills && cd ~/.claude/skills

# Clone this repo
git clone https://github.com/bdnhost/claude-skills.git bdnhost-src

# Copy the skill you want
cp -R bdnhost-src/skills/lahav433 ./lahav433
# Or pick another from skills/

# Claude Code auto-discovers — just invoke it in a session
```

### Or paste this prompt into Claude Code

```
Install the Claude Code skill "lahav433" from
https://github.com/bdnhost/claude-skills — clone into
/tmp/bdnhost-src, copy the skill folder to ~/.claude/skills/,
verify SKILL.md frontmatter, and show me a short usage example.
```

---

## Browse all 250+ skills

The full registry catalogs **every public Claude Code skill we can find**, classified by category, source repo, language, and tags.

| | |
|---|---|
| 🔎 **Search & filter** | [claude-skills.bdnhost.net](https://claude-skills.bdnhost.net/) |
| 📡 **Daily updates** | Auto-discovered from GitHub at 06:00 UTC |
| 🌐 **Languages** | English · Hebrew · Chinese (mixed where relevant) |
| 📦 **Categories** | Code, DevOps, Frontend, Data, AI/ML, Security, Cloud, Integrations, Documents, Creative, Content, Business, Meta, Localization, Specialized |
| 📤 **Subscribe** | Weekly digest of new skills (no spam, double opt-in) |

---

## About BDNHOST

We build AI-driven SaaS platforms — [EduManage LMS](https://edu-manage.org), [Israel Estates](https://israel-estates.com), [LegalNexus](https://legalnexus.top), [CompanyRadar](https://companyradar.top), [CRM4BIZ](https://crm4biz.top), [SalaryLens](https://salarylens.app). When a skill we build for one platform has broader value, we open-source it here.

- 🌐 [bdnhost.net](https://bdnhost.net) — main site
- 📧 [info@bdnhost.net](mailto:info@bdnhost.net)
- 💼 [linkedin.com/in/bdnhost](https://www.linkedin.com/in/bdnhost)
- 🎓 [Claude Code Bootcamp (Hebrew)](https://bootcamp.edu-manage.org/landing/claude-code.html)

---

## License

MIT — unless a skill specifies otherwise in its `SKILL.md` frontmatter. Individual skills may reference third-party data (laws, government databases, etc.) that remain property of their respective owners.

---

## Contributing

This repo is curated by BDNHOST. To propose a skill, **open an issue first** — skills should be:

- Generic enough to be useful to others (not tightly coupled to internal infra)
- Verified against the [official SKILL.md spec](https://docs.claude.com/en/docs/claude-code/skills)
- Tested with at least one real session in Claude Code

For non-BDNHOST skills, add them to your own repo and they'll get picked up by the [auto-discovery workflow](https://claude-skills.bdnhost.net/#about) within 24h — no PR needed.
