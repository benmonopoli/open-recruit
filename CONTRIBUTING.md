# Contributing to Open Recruit

Thanks for your interest in contributing. The goal of this library is simple: give recruiters and AI tools specialist-level knowledge for specific hiring disciplines. Every skill in the library was built by synthesising the best available practitioner knowledge — not generic advice — into a reusable format.

If you've hired in a discipline not covered here, or you've found a gap in an existing skill, contributions are very welcome.

---

## What makes a good skill

The best skills in this library work because they encode how an experienced specialist actually operates — not what a textbook says they should do.

Before writing a skill, ask yourself:

- **Does this reflect how practitioners actually work?** Not how the job description reads, but how someone with 5+ years in this discipline would approach it.
- **Is it specific enough to be useful?** "Marketing hiring" is too broad. "Performance marketing hiring" is specific. "Google Ads hiring for e-commerce" is very specific.
- **Is it additive?** Check whether an existing skill already covers this. If it's close, consider opening an issue to discuss extending it rather than duplicating.

---

## Skill structure

Each skill lives in its own folder under the appropriate category:

```
skills/
  tech-hiring/
    tech-hiring-backend-engineering/
      SKILL.md
  marketing-hiring/
    marketing-hiring-seo-organic-search/
      SKILL.md
  sales-hiring/
    sales-hiring-account-executive-enterprise-strategic/
      SKILL.md
```

### Required: SKILL.md

Every skill needs a `SKILL.md` file. The file should open with:

```
---
name: [Skill name, matching the folder name]
description: [One sentence. What this skill does and who it's for.]
---
```

After the frontmatter, the skill content is free-form — write what's most useful for that discipline. Good skills typically cover:

- Role overview and what "good" looks like at different levels
- T1/T2/T3 criteria (must-have, differentiator, rare upside)
- Sourcing strategy and platform guidance
- Screening signals and red flags
- Interview approach and evaluation signals
- Common mistakes when hiring for this role
- Seniority calibration

There's no required template — structure it in whatever way makes the skill most useful in practice.

---

## How to contribute

### Adding a new skill

1. Fork the repository
2. Create a folder under the appropriate category in `skills/`
3. Add a `SKILL.md` file with the skill content
4. Open a pull request with:
   - A short description of what the skill covers
   - How you've used it (or validated it) in practice
   - Which AI tools you've tested it with, if relevant

### Improving an existing skill

If you've found an error, an outdated signal, or a meaningful gap in an existing skill:

1. Fork the repository
2. Edit the relevant `SKILL.md`
3. Open a pull request describing what you changed and why

### Suggesting a new skill

If you want to propose a skill but aren't ready to write it, open an issue using the **New skill** template. Include what discipline it would cover and what you'd expect it to do. Someone else may pick it up.

### Reporting a problem

If a skill produces poor or misleading output in practice, open a bug report. Include the prompt or workflow you used and what the issue was.

---

## Pull request checklist

Before submitting:

- [ ] The skill is in the correct category folder
- [ ] The folder name matches the skill name in the frontmatter
- [ ] The `SKILL.md` opens with valid frontmatter (`name` and `description`)
- [ ] The content reflects genuine practitioner knowledge, not generic advice
- [ ] If adding to the routing engine (`CLAUDE.md`), the new skill is referenced correctly

---

## Formatting

- Use plain Markdown
- Keep prose direct and specific — this is a practitioner tool, not a document
- Avoid generic filler ("it's important to...", "you should consider...") — state the thing directly
- Headings, bullet points, and tables are all fine where they help readability

---

## Questions

If you're unsure whether something fits, open an issue before writing the skill. Better to align early than to write something that doesn't get merged.
