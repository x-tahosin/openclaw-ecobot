<div align="center">

# 🤖 EcoBot — OpenClaw Skill

**Personal Carbon Footprint Tracker & Green Living Advisor**

[![Challenge](https://img.shields.io/badge/OpenClaw_Challenge-DEV.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/tahosin/ecobot-a-personal-carbon-footprint-tracker-built-with-openclaw-2e02)

![OpenClaw](https://img.shields.io/badge/OpenClaw-FF5722?style=flat-square)
![Markdown](https://img.shields.io/badge/SKILL.md-000?style=flat-square&logo=markdown)

</div>


## 📖 Deep Dive

This project is one of 5 AI apps I shipped on Google's Gemini free tier. I wrote up the exact architecture, cost breakdown, and what breaks first in production:

**[$0/Month, 5 AI Apps, All on Gemini: Here's Exactly What the Free Tier Gives You (and What Breaks First)](https://dev.to/tahosin/0month-5-ai-apps-all-on-gemini-heres-exactly-what-the-free-tier-gives-you-and-what-breaks-58fl)** — on Dev.to

---

## What It Does

A single `SKILL.md` file that turns OpenClaw into an environmental advisor:

- 🌍 **Carbon Footprint Check** — estimates annual CO2 from your habits
- 💡 **Eco Tip of the Day** — actionable tips with CO2 savings
- 🔍 **Product Eco Check** — web search for product environmental impact
- 📝 **Habit Logger** — tracks green actions in a local JSON file
- 📊 **Weekly Report** — summarizes eco progress over time

## Install

```bash
cp -r skills/ecobot ~/.openclaw/workspace/skills/
openclaw gateway restart
```

## Usage

```
> "What's my carbon footprint?"
> "Give me an eco tip"
> "How bad is fast fashion for the environment?"
> "I biked to work today"
> "Show me my weekly green report"
```

## Built For

[OpenClaw Challenge on DEV.to](https://dev.to/challenges/openclaw-2026-04-16) — $1,200 prize pool

---

<div align="center">

Made with 💚 by [Tahosin](https://github.com/x-tahosin)

</div>
