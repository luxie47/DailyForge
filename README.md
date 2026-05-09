# ⚡ DailyForge — Prompt Engineering Skill for Claude

> **The most complete prompt engineering system built as a Claude Skill.**  
> Engineer, debug, translate, compare, score, and batch-build master prompts — all inside Claude.

**Made by [luxie47](https://github.com/luxie47) · [daily-origin.vercel.app](https://daily-origin.vercel.app)**

---

![DailyForge Banner](https://raw.githubusercontent.com/luxie47/DailyForge/main/banner.png)

![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0.0-orange?style=for-the-badge)

---

## What is DailyForge?

DailyForge is a Claude Skill that transforms how you write prompts. Instead of guessing what works, it walks you through a structured category-by-category process to build powerful master prompts — then scores them, lets you refine them, and saves them for reuse.

Part of the **Daily** app family by luxie47.

---

## Features

| Feature | Command |
|---|---|
| Engineer a master prompt | `/dailyforge [your prompt idea]` |
| Debug a failing prompt | `/dailyforge debug` or say `prompt debug` |
| Translate from GPT/Gemini to Claude | `/dailyforge translate` or say `prompt translate` |
| Compare two prompts | `/dailyforge compare` or say `prompt compare` |
| Build 3 variations at once | `/dailyforge batch` |
| Score any prompt (1–10) | `/dailyforge score` |
| Get starter templates | `/dailyforge template [category]` |
| Learn one prompt tip | `/dailyforge tip` |
| Export to Markdown/Notion/Plain | `/dailyforge export [format]` |
| Save, list, recover prompts | `/dailyforge save` · `list` · `history` |
| Auto-engineer every message | `/dailyforge mode on` |

---

## Install in Claude

### Method 1 — Upload ZIP (Easiest)

1. Download this repo as a ZIP → click green **Code** button → **Download ZIP**
2. Go to **Claude.ai**
3. Click your profile → **Customize Claude** → **Skills**
4. Click the **+** icon → **Create Skill**
5. Upload the ZIP file
6. Done — type `/dailyforge` to start

### Method 2 — Copy & Paste (Manual)

1. Open [`SKILL.md`](./SKILL.md) in this repo
2. Select all → copy everything
3. Go to **Claude.ai → Settings → Skills**
4. Click **+** → **Create Skill**
5. Paste into the skill body
6. Set skill name: `dailyforge`
7. Copy the description line from the top of SKILL.md (between the `---` lines) into the description field
8. Save — type `/dailyforge` to start

> **Important:** The description field is what tells Claude when to activate this skill. Copy it exactly from the SKILL.md frontmatter.

---

## Quick Start

```
/dailyforge I want to write cold emails for my SaaS product
```

DailyForge asks questions across 7 categories, one at a time, then delivers a complete master prompt — scored, structured, ready to use.

---

## Keyword Shortcuts

No prefix needed for these:

- Say **`prompt debug`** → diagnoses your failing prompt
- Say **`prompt translate`** → converts GPT/Gemini prompts to Claude format  
- Say **`prompt compare`** → compares two prompts, picks the winner

---

## Full Command Reference

```
/dailyforge [prompt]         → Engineer a master prompt
/dailyforge refine           → Refine with before/after diff
/dailyforge batch            → Build 3 prompt variations
/dailyforge score            → Score last prompt (1–10 breakdown)
/dailyforge save [name]      → Save prompt with name
/dailyforge list             → Show all saved prompts
/dailyforge history          → Show last 5 built prompts
/dailyforge reset            → Clear all saves and context
/dailyforge debug            → Diagnose a failing prompt
/dailyforge translate        → Convert from other AI to Claude
/dailyforge compare          → Compare two prompts, pick winner
/dailyforge challenge        → Improve a bad prompt, get scored
/dailyforge template [cat]   → Starter templates by category
/dailyforge tip              → One prompt engineering insight
/dailyforge export [format]  → Export as markdown/notion/plain
/dailyforge mode on/off      → Auto-engineer every message
/dailyforge guide            → Full command reference in Claude
```

---

## Why DailyForge?

Most people write prompts by trial and error. DailyForge makes it a system:

- **Structured** — 7-category questioning, nothing missed
- **Scored** — every prompt rated 1–10 with specific feedback
- **Debuggable** — diagnose exactly why a prompt fails
- **Cross-AI** — translate GPT/Gemini prompts to Claude format
- **Memory** — save, list, recover prompts within a session

---
## Example — Full 7-Category Flow

**User:** `/dailyforge write cold emails for a SaaS product`

**DailyForge asks:**
1. Goal: What action should the reader take?
2. Audience: Who are you targeting? Job title, industry?
3. Tone: Formal, casual, bold?
4. Constraints: Max length? Avoid any words/phrases?
5. Role: Should Claude act as a sales expert, founder, copywriter?
6. Output format: Subject line + body? Bullet points?
7. What NOT to do: No pushy language? No generic openers?

**Result:** Complete master prompt delivered in a code block, auto-scored.

## License

MIT — see [LICENSE](./LICENSE)

Free to use, share, and build on. **Please credit luxie47** when sharing.

---

**Made by [luxie47](https://github.com/luxie47)** · [daily-origin.vercel.app](https://daily-origin.vercel.app)

⭐ If DailyForge helped you, star this repo — it helps others find it.
