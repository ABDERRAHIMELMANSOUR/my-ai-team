# My AI Team

A multi-agent workflow for web development and digital marketing. A lead agent runs each job, specialist agents do the work, and a human approves anything that goes live or spends money.

## How it fits together

| Folder | What it holds |
|---|---|
| [AGENTS.md](AGENTS.md) | The rules every agent follows: roles, handoffs, gates |
| [.claude/agents/](.claude/agents/) | One definition per specialist |
| [workflows/](workflows/) | Step-by-step playbooks for each kind of job |
| [standards/](standards/) | The quality bar for web and marketing work |
| [templates/](templates/) | Reusable documents agents fill in |
| [projects/_template/](projects/_template/) | Starting folder for each new job |
| [docs/](docs/) | Team process, cross-review protocol and the ALM/CPA strategy |

These files define roles and working practices. They do not connect accounts or run campaigns on their own.

## The team

| Agent | Owns |
|---|---|
| Lead (the main session) | Planning, delegation, status, gates |
| [strategist](.claude/agents/strategist.md) | Research, positioning, audience, offer |
| [ux-designer](.claude/agents/ux-designer.md) | Page structure, flows, design direction |
| [copywriter](.claude/agents/copywriter.md) | Site, ad and email copy |
| [web-developer](.claude/agents/web-developer.md) | Building and fixing the site |
| [seo-specialist](.claude/agents/seo-specialist.md) | Keywords, on-page and technical SEO |
| [paid-media](.claude/agents/paid-media.md) | Campaign plans and ad variants |
| [analytics](.claude/agents/analytics.md) | Tracking plans and performance reports |
| [qa-reviewer](.claude/agents/qa-reviewer.md) | Independent check before each launch |

## Workflows

- [Website build](workflows/website-build.md): from brief to a launched site
- [Campaign launch](workflows/campaign-launch.md): landing page and paid ads
- [Monthly growth](workflows/monthly-growth.md): recurring SEO, content and ad optimization

## Starting a job

1. Copy `projects/_template/` to `projects/<client-or-job-slug>/`.
2. Fill in `brief.md` and `brand.md`, or ask the lead to interview you.
3. Open Claude Code in this repo and say which workflow to run on which project.

## Privacy

This repo is public, so `.gitignore` keeps everything under `projects/` out of Git except the template. To version client work here, make the repo private first, then remove the two `projects/` lines from `.gitignore`.
