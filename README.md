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

## Quick Start

```bash
python3 -m http.server 8080
```

Then open: `http://localhost:8080/skillsync-complete.html`

## File Structure

```
SkillSync/
├── skillsync-complete.html   # Main app (HTML + CSS + JS)
├── README.md
```
