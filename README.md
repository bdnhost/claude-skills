# BDNHOST Claude Skills

Public Claude Code Skills authored by **BDNHOST Group**.
Curated for production use, Hebrew-first where relevant, verified against the official SKILL.md spec.

🔗 Discover all skills: [claude-skills.bdnhost.net](https://claude-skills.bdnhost.net/)

---

## Available Skills

### ⭐ `lahav433` · Investigative Journalism Engine
FBI-grade OSINT + Intelligence Cycle methodology for autonomous newsrooms. Integrates forensic accounting (Benford's Law, tender compliance under Israeli law) and pre-publication legal review. Triple-source verification, defamation-safe language transformation, and Hebrew/English support.

**Activates on:** "investigate", "audit tenders", "follow the money", "check budget anomalies", "חקור", "בדוק מכרזים", OSINT, Intelligence Cycle, forensic accounting.

---

## Install

Each skill is a self-contained folder under `skills/`.

```bash
# Navigate to your Claude Code skills dir
mkdir -p ~/.claude/skills && cd ~/.claude/skills

# Clone this repo
git clone https://github.com/bdnhost/claude-skills.git bdnhost-src

# Copy the skill you want
cp -R bdnhost-src/skills/lahav433 ./lahav433

# Enable in Claude Code
# (just invoke it — Claude Code auto-discovers skills in ~/.claude/skills/)
```

---

## About BDNHOST

BDNHOST Group builds AI-driven SaaS platforms — EduManage LMS, Israel Estates, LegalNexus,
CompanyRadar, CRM4BIZ, SalaryLens, and more. We open-source production skills we use
internally when they have broader value.

- 🌐 https://bdnhost.net
- 📧 info@bdnhost.net
- 💼 https://www.linkedin.com/in/bdnhost
- 📚 https://edu-manage.org/PublicCourses — Claude Code courses in Hebrew

---

## License

MIT — unless a skill specifies otherwise in its own `SKILL.md` frontmatter.
Individual skills may contain third-party references (Israeli laws, government databases, etc.) that remain property of their respective owners.

---

## Contributing

This repo is currently curated by BDNHOST. To propose a skill, open an issue first.
