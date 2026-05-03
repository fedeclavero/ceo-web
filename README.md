# CEO-Web

Multi-agent orchestrator for full-stack web development. Uses a hierarchical business model: CEO -> Managers -> Specialized Engineers.

## Installation

```bash
npx skills add fedeclavero/ceo-web
```

## What It Does

Builds complete websites by delegating each aspect to a specialized engineer:

- **Planning Manager** — converts requirements into an action plan
- **Review Manager** — final quality, security, and design audit
- **Deploy Engineer** — researches platform constraints
- **Creative Engineer** — defines design, colors, typography, mood
- **Assets Engineer** — searches and downloads images, SVGs, fonts
- **Frontend Engineer** — builds vanilla HTML/CSS/JS
- **Adaptive Engineer** — responsive, dark/light mode, cross-browser
- **Backend Engineer** — functionality, APIs, logic
- **SEO Engineer** — metatags, schema.org, GEO optimization

## Workflow

```
Human -> CEO -> Planning Manager -> Engineers (sequential)
                -> Review Manager -> CEO (testing) -> Human
                ^--- iterations (max 4) ---|
```

## Prerequisites

Some engineers need additional skills. If an engineer is missing a skill, the CEO will tell you with the link to install it:

| Engineer | Required Skills |
|----------|----------------|
| Planning | `brainstorming`, `writing-plans` |
| Creative | `frontend-design`, `web-design-guidelines`, `ui-ux-pro-max` |
| Assets | `agent-browser` |
| Frontend | `frontend-design`, `web-design-guidelines`, `ui-ux-pro-max` |
| Adaptive | `adapt` |
| Deploy | `cloudflare` |
| SEO | `seo-geo`, `seo-audit` |
