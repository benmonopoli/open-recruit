# Open Recruit

A collection of AI recruiting skills — reusable instruction sets that give AI tools specialist-level knowledge for specific recruiting disciplines.

Built and open-sourced by [@benmonopoli](https://github.com/benmonopoli).



---

## What are skills?

A skill is a reusable instruction set that teaches an AI tool how to perform a specific task at a specialist level. Instead of writing a new prompt every time, you define the expertise once and load it whenever you need it.

From that point the AI isn't working from general knowledge — it's working from a structured, practitioner-level understanding of that discipline. The difference in output quality is significant. A sourcing skill doesn't just write a Boolean string — it knows the role variants experienced recruiters search for, the platforms where the best candidates actually spend time, and the signals that indicate genuine seniority versus surface-level experience.

> Skills are currently optimised for [Claude](https://claude.ai) by Anthropic, but the structure and patterns can be adapted for other AI platforms.

---

## What's included

### Sourcing

| Skill | Description |
|-------|-------------|
| **linkedin-recruiting** | Find, evaluate, and engage candidates on LinkedIn. Boolean strings, InMails, profile review, pipeline building, market mapping. |
| **github-sourcing** | Source technical candidates through GitHub activity, contributions, and repositories. |
| **web-sourcing** | Advanced Google X-Ray search, portfolio sites, conference speaker lists, and open web sourcing. |
| **x-recruiting** | Source candidates on X using Advanced Search operators, Boolean strings, and X-Ray search. |
| **google-scholar-sourcing** | Find academic and research-oriented candidates through publications and citations. |
| **sourcing-communities** | Source from professional communities, forums, Slack groups, Discord servers, and online meetups. |
| **sourcing-tools-stack** | Build and optimise your recruiting sourcing tech stack. |
| **ai-recruiting-prompts** | AI prompts and templates for common recruiting workflows. |
| **greenhouse-recruiting** | Manage candidates, jobs, and pipelines in Greenhouse via the Harvest API. |

### Tech Hiring — `skills/tech-hiring/`

| Skill | Description |
|-------|-------------|
| **tech-hiring-backend-engineering** | Server-side development, APIs, databases, distributed systems. |
| **tech-hiring-frontend-engineering** | Web applications, design systems, accessibility, client-side performance. |
| **tech-hiring-data-science** | Statistical modelling, machine learning, data analysis. |
| **tech-hiring-machine-learning-ai-engineering** | Model development, training infrastructure, production ML systems. |
| **tech-hiring-data-engineering** | Data pipelines, ETL/ELT, data warehousing, big data. |
| **tech-hiring-devops-platform-engineering** | CI/CD, infrastructure automation, developer experience. |
| **tech-hiring-infrastructure-cloud-engineering** | Cloud platforms, networking, systems architecture. |
| **tech-hiring-mobile-engineering** | iOS, Android, cross-platform development. |
| **tech-hiring-security-engineering** | Application security, infrastructure security, SecOps. |
| **tech-hiring-qa-test-engineering** | Test automation, quality strategy, testing frameworks. |
| **tech-hiring-search-crawler-infrastructure** | Web crawling, indexing, search ranking, large-scale data collection. |
| **tech-hiring-browser-extension-engineering** | WebExtensions APIs, cross-browser development, extension architecture. |

### Marketing Hiring — `skills/marketing-hiring/`

| Skill | Description |
|-------|-------------|
| **marketing-hiring-content-marketing** | Content strategy, editorial planning, content creation. |
| **marketing-hiring-seo-organic-search** | Technical SEO, content SEO, link building, search strategy. |
| **marketing-hiring-performance-marketing-paid-media** | Paid search, paid social, display, programmatic. |
| **marketing-hiring-product-marketing** | Positioning, messaging, competitive intelligence, launch strategy. |
| **marketing-hiring-brand-marketing** | Brand strategy, positioning, visual identity. |
| **marketing-hiring-growth-marketing** | Experimentation, acquisition, activation, retention. |
| **marketing-hiring-email-lifecycle-marketing** | Email campaigns, automation, segmentation, nurture flows. |
| **marketing-hiring-developer-relations-devrel** | Developer advocacy, documentation, technical community. |
| **marketing-hiring-community-marketing** | Community building, engagement programs, advocacy. |
| **marketing-hiring-social-media-marketing** | Social strategy, content, community management, analytics. |
| **marketing-hiring-marketing-operations** | Martech stack, automation, analytics, process optimisation. |
| **marketing-hiring-copywriting** | Persuasive writing, brand voice, conversion copy. |
| **marketing-hiring-localisation** | Translation management, cultural adaptation, international content. |
| **marketing-hiring-influencer-marketing** | Influencer partnerships, creator programs, sponsored content. |
| **marketing-hiring-partnerships-business-development** | Strategic partnerships, co-marketing, alliance management. |
| **marketing-hiring-gotomarket-gtm** | Launch strategy, market positioning, GTM coordination. |
| **marketing-hiring-field-marketing-events** | Event planning, trade shows, regional marketing. |
| **marketing-hiring-pr-communications** | Media relations, press strategy, corporate communications. |
| **marketing-hiring-enterprise-marketing-abm** | Account-based marketing, enterprise campaigns. |
| **marketing-hiring-marketing-generalist** | Multi-channel marketing, campaign management. |
| **marketing-hiring-marketing-leadership** | CMO/VP-level strategy, team building, budget management. |
| **marketing-hiring-video-marketing** | Video strategy, production, editing, distribution. |

### Sales Hiring — `skills/sales-hiring/`

| Skill | Description |
|-------|-------------|
| **sales-hiring-sdr-bdr** | Outbound prospecting, inbound qualification, pipeline generation. |
| **sales-hiring-account-executive-midmarket** | Full-cycle sales, pipeline management, quota attainment. |
| **sales-hiring-account-executive-enterprise-strategic** | Complex deal cycles, C-suite selling, strategic accounts. |
| **sales-hiring-account-manager** | Client retention, upselling, cross-selling, relationship management. |
| **sales-hiring-customer-success-manager-csm** | Onboarding, adoption, retention, expansion. |
| **sales-hiring-solutions-engineer-sales-engineer** | Technical demos, proof of concepts, pre-sales support. |
| **sales-hiring-sales-leadership** | VP/Director-level sales management, team building, revenue strategy. |
| **sales-hiring-sales-operations** | Forecasting, territory planning, compensation, CRM management. |
| **sales-hiring-revenue-operations-revops** | Sales analytics, process optimisation, GTM alignment. |
| **sales-hiring-sales-enablement** | Training, content, tools, sales productivity programs. |
| **sales-hiring-channel-partner-sales** | Partner recruitment, enablement, indirect revenue. |
| **sales-hiring-renewal-manager** | Contract renewals, churn prevention, retention strategies. |
| **sales-hiring-inside-sales** | High-velocity selling, demos, remote deal closing. |
| **sales-hiring-accounts-receivable-specialist** | Invoicing, collections, payment processing. |

---

## Getting started

### Install as a plugin (recommended)

```bash
/plugin install benmonopoli/AI-Recruiting-Skills
```

### Manual install

1. Clone the repo:
   ```bash
   git clone https://github.com/benmonopoli/AI-Recruiting-Skills.git
   ```
2. Copy the skills you need into your AI tool's skills directory
3. Load a skill and start using it

---

## Contributing

The library covers what I hire for — there are plenty of disciplines it doesn't touch. If you've built skills that work for your recruiting context, contributions are welcome.

1. Create a folder under the appropriate category in `skills/`
2. Add a `SKILL.md` file with your skill's instructions
3. Include YAML frontmatter with `name` and `description` fields at the top
4. Open a pull request with a clear description of what the skill does

If you've built something useful in a different format or for a different platform, open an issue and let's figure out how it fits.

---

## License

MIT — use it, build on it, share what you make.
