<p align="center">
  <img src="images/studentclaw-logo.svg" alt="StudentClaw" width="140"/>
</p>

<h1 align="center">🎓 StudentClaw</h1>

<p align="center">
  <b>Your personal AI study assistant — powered by your Claude subscription.<br>No bans, no extra costs, open-source.</b>
</p>

---

## What is StudentClaw?

StudentClaw turns your Claude Code subscription into a 24/7 AI study buddy. Runs as a background daemon on any device — laptop, VPS, Raspberry Pi.

**Already paying for Claude Pro (~$20/month)? You get this for free.** No API keys, no extra charges.

## What it does for students

- 📚 **Essay & paper help** — ask via Telegram, get structured feedback
- 📝 **Lecture summarizer** — send a recording or PDF, get key points
- 🗓️ **Study scheduler** — set reminders for deadlines and exam prep
- 🔊 **Voice commands** — send voice messages, it transcribes and responds
- ⏰ **Always-on daemon** — schedules tasks, morning briefings, deadline alerts
- 🌍 **Works from anywhere** — Telegram bot interface, no app needed

## Why not just use Claude.ai?

| Feature | Claude.ai | StudentClaw |
|---------|-----------|-------------|
| Scheduled reminders | No | Yes |
| Telegram bot interface | No | Yes |
| Voice message support | No | Yes |
| Runs 24/7 in background | No | Yes |
| Extra cost | No | No |
| Works with Claude Pro $20/mo | — | Yes |

## Getting Started in 5 Minutes

```bash
claude plugin marketplace add Aleschka/studentclaw
claude plugin install studentclaw
```

Then set up your Telegram bot token in `.env` and you are ready.

## Setup

1. Get a free Telegram bot via @BotFather on Telegram
2. Clone this repo or install via Claude plugin marketplace
3. Add your bot token to `.env`
4. Run: `claude plugin start studentclaw`

## Requirements

- Claude Code + any Claude subscription (Pro works fine)
- Node.js 18+
- Telegram account

## Built on ClaudeClaw

StudentClaw is a focused fork of ClaudeClaw by moazbuilds, optimized for student workflows.

---

Have a Claude subscription? You already have everything you need.
