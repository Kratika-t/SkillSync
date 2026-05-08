# SkillSync

A single-file HTML/CSS/JS web application for employee skill tracking, AI-assisted learning, and HR analytics.

## Features

- **Employee Dashboard** — Skill scores, training progress, assessments
- **AI Chatbot** — Contextual mock AI assistant with conversation history
- **Skill Analysis** — Dynamic SVG radar chart + gap analysis
- **My Progress** — Learning timeline and weekly activity chart
- **Knowledge Repository** — Searchable cards with bookmarking
- **HR Dashboard** — Employee overview, alerts, CSV export
- **AI Quiz Generator** — Topic/difficulty selector with mock question banks

## Tech Stack

- Single HTML file (no build step, no external JS libraries)
- Vanilla JavaScript with localStorage persistence
- CSS variables + responsive design
- Python HTTP server for local development

## Quick Start (Local)

```bash
python3 -m http.server 8080
```

Then open: `http://localhost:8080/skillsync-complete.html`

## Deployment (Vercel)

This is a static HTML site — ready to deploy on [Vercel](https://vercel.com) in one click.

### Option 1: Vercel CLI

```bash
npm i -g vercel
vercel --prod
```

### Option 2: GitHub + Vercel Dashboard

1. Push this repo to GitHub (already done)
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import `Kratika-t/SkillSync`
4. Framework preset: **Other** (static)
5. Deploy

> **Note:** For clean URLs, rename `skillsync-complete.html` → `index.html` before deploying, or configure a Vercel redirect in `vercel.json`.

### `vercel.json` (optional — for clean URLs)

```json
{
  "rewrites": [
    { "source": "/", "destination": "/skillsync-complete.html" }
  ]
}
```

## File Structure

```
SkillSync/
├── skillsync-complete.html   # Main app (HTML + CSS + JS)
├── README.md
└── vercel.json               # Optional: URL rewrites
```
