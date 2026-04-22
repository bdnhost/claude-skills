# BDNHOST Claude Skills

Public Claude Code Skills authored by **BDNHOST Group**.
Production-grade, Hebrew-first where relevant, verified against the official SKILL.md spec.

🔗 **Discover all skills + live catalog:** [claude-skills.bdnhost.net](https://claude-skills.bdnhost.net/)

---

## Available Skills

### ⭐ `lahav433` · Investigative Journalism Engine
FBI-grade OSINT + Intelligence Cycle methodology for autonomous newsrooms. Integrates forensic accounting (Benford's Law, Israeli procurement compliance) and pre-publication legal review. Triple-source verification, defamation-safe language transformation, Hebrew + English.

**Activates on:** "investigate", "audit tenders", "follow the money", "check budget anomalies", "חקור", "בדוק מכרזים", OSINT, Intelligence Cycle, forensic accounting.

**Category:** Specialized Domains · **Language:** Hebrew, English · **Verified**

---

### 🏛️ `journalism-legal-il` · Israeli Press-Law Advisor
Standing legal advisor for small Israeli news outlets. Covers defamation (חוק איסור לשון הרע, תשכ"ה-1965), privacy (חוק הגנת הפרטיות, תשמ"א-1981), Freedom of Information Act (חוק חופש המידע, תשנ"ח-1998), source protection, and takedown handling. Produces safe-to-publish edited versions + change explanations.

**Activates on:** "is this defamation?", "can I publish this?", "received a lawyer letter", source protection, FOIA, photo publication of residents/minors, "האם מותר לפרסם", "לשון הרע", "מכתב עו"ד".

**Category:** Specialized Domains · **Language:** Hebrew, English · **Verified**

> ⚠️ Not a substitute for licensed legal counsel on high-stakes matters.

---

## Install

Each skill is a self-contained folder under `skills/`.

```bash
# Navigate to your Claude Code skills dir
mkdir -p ~/.claude/skills && cd ~/.claude/skills

# Clone this repo
git clone https://github.com/bdnhost/claude-skills.git bdnhost-src

# Copy the skill you want
cp -R bdnhost-src/skills/journalism-legal-il ./journalism-legal-il
# or
cp -R bdnhost-src/skills/lahav433 ./lahav433

# Claude Code auto-discovers skills in ~/.claude/skills/ — just invoke
```

### Or use a Claude Code prompt (paste into your Claude Code session)

```
Install the Claude Code skill "journalism-legal-il" from
https://github.com/bdnhost/claude-skills — clone into
/tmp/bdnhost-src, copy the skill folder to ~/.claude/skills/,
verify SKILL.md frontmatter, and show me a short usage example.
```

---

## About BDNHOST

BDNHOST Group builds AI-driven SaaS platforms — EduManage LMS, Israel Estates, LegalNexus, CompanyRadar, CRM4BIZ, SalaryLens, and more. We open-source production skills when they have broader value.

- 🌐 https://bdnhost.net
- 📧 info@bdnhost.net
- 💼 https://www.linkedin.com/in/bdnhost
- 📚 https://edu-manage.org/PublicCourses — Claude Code courses in Hebrew

---

## License

MIT — unless a skill specifies otherwise in its `SKILL.md` frontmatter. Individual skills may contain third-party references (Israeli laws, government databases, etc.) that remain property of their respective owners.

---

## Contributing

This repo is curated by BDNHOST. To propose a skill, open an issue first — skills should be generic enough to be useful to others, not tightly coupled to internal BDNHOST infrastructure.
