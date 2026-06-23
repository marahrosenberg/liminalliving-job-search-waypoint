# LiminalLiving — Job Search Waypoint

### A grief-literate resume and cover letter system for job seekers

*Developed by [Liminal Living](https://liminalliving.net) | CC BY-NC 4.0*

---

## What this is

A Claude skill that guides job seekers through a rigorous, structured resume and cover
letter process — while holding the emotional reality of what job loss actually feels like.

A waypoint is not a destination. It's a fixed point that helps you know where you are
so you can keep moving. That's what this tool is.

Most resume tools treat the human as a variable to manage around. This one treats human
capacity as the system itself.

You don't need a job description to start. You don't need a resume ready or a role in
mind. You can arrive exactly where you are — stuck, numb, not sure what you're doing
next — and that's enough to begin. Claude will ask for what it needs, when it needs it.

This works for:
- Recent layoffs navigating shock and momentum at the same time
- Long searches where confidence has eroded
- Career changers with non-linear histories
- Anyone who's been told their background "doesn't fit" and knows that's not the whole story
- Anyone who just needs somewhere to land while they figure out what's next

---

## What it does

- Deconstructs job descriptions to identify the core problem the role is meant to solve
- Identifies keyword tiers and maps cross-domain experience to role requirements
- Generates ATS-optimized bullets using the Victory Bullet Formula
- Writes cover letters with a T-shape structure (450 words max)
- Runs a full QA checklist before delivery — including an anti-AI writing check
- Delivers: resume draft + cover letter + ATS Compliance Report + 3 interview talking points

It also knows when to pause the protocol and ask: *"What's making this feel hard right now?"*

---

## Before you install

**Do you have a paid Claude subscription (Pro or Max)?**

This determines how you set up Waypoint. Both paths work — they just feel different.

- **Free account** → You'll paste the skill into each conversation. Takes about 60 seconds. Jump to [Free Setup](#free-account-setup).
- **Paid account (Pro or Max)** → You'll install it once and it persists across all your conversations. Jump to [Pro/Max Setup](#promax-account-setup).

Not sure which you have? If you signed up without a credit card, you're on the free plan.

---

## Free Account Setup

You don't need to install anything. You'll paste the skill at the start of each conversation.

**What you'll need:**
- The contents of `SKILL.md` (the main skill file)
- The contents of `references/protocol.md` (the full workflow)
- A job description, or just a place to start — Claude will ask for what it needs

**Step 1: Get the files**

1. On this GitHub page, click the green **Code** button (top right of the file list)
2. Select **Download ZIP**
3. Unzip the downloaded file on your computer
4. Open `SKILL.md` in any text editor (Notepad, TextEdit, etc.) and copy all the text
5. Do the same for `references/protocol.md`

**Step 2: Start a conversation**

1. Go to [claude.ai](https://claude.ai) and start a new conversation
2. Paste the full contents of `SKILL.md` into the chat
3. Then paste the full contents of `references/protocol.md`
4. Send a message to get started (see examples below)

Claude will ask for your resume and any other materials when it's ready to use them.

**Step 3: Invoke the skill**

After pasting, send a message like one of these to get started:

> "I want to apply to this role. Here's the job description. Please run the Waypoint protocol."

> "I don't know if I'm qualified for this. Can you help me figure out if I should apply?"

> "I'm not sure where to start. I just lost my job and I don't know what to do next."

**Note:** You'll repeat steps 2–3 at the start of each new conversation. Claude doesn't
retain files or context between sessions on the free plan.

---

## Pro/Max Account Setup

Install Waypoint once. It will be available in every future conversation automatically.

**Step 1: Download the skill**

1. On this GitHub page, click the green **Code** button (top right of the file list)
2. Select **Download ZIP**
3. Save the ZIP file somewhere you can find it (Downloads folder is fine)
   — do not unzip it

**Step 2: Install the skill in Claude**

1. Go to [claude.ai](https://claude.ai)
2. Click the **menu icon** (top left) to open the sidebar
3. Click **Customize**
4. Click **Create new skills**
5. Click the **+** (plus) button
6. Select **Create skill**
7. Click **Upload a skill**
8. Select the `.zip` file you downloaded in Step 1
9. Click **Create** — you should see Waypoint appear in your skills list

**Step 3: Store your resume (optional but recommended)**

Claude Projects let you store your resume so it's available in every session without
re-uploading.

1. In the Claude sidebar, click **New Project** (or open an existing one)
2. Click **Add content** or the paperclip icon
3. Upload your resume as a file
4. Name the project something like "Job Search" so it's easy to find

**Step 4: Start a conversation and invoke the skill**

Waypoint doesn't activate automatically — you need to tell Claude you want to use it.
Start a new conversation (inside your Job Search project if you set one up) and say
something like:

> "I want to apply to this role. Please use the Waypoint skill. Here's the job description: [paste JD]"

> "Use Waypoint. I'm not sure where to start — I just need to talk through where I am."

> "Run the Waypoint protocol. Here's what I'm working with: [paste whatever you have]"

Claude will confirm it's using the skill and ask for what it needs from there.

---

## How to start a conversation

These phrases work for both free and paid users once the skill is active:

| What you want | What to say |
|---|---|
| Apply to a specific role | "I want to apply to this role. [paste job description]" |
| Fix a single bullet | "Help me strengthen this bullet: [paste bullet]" |
| Check ATS compliance | "Run an ATS check on my resume" |
| Write a cover letter | "Write a cover letter for this role" |
| Figure out if you should apply | "I don't know if I'm qualified. Can you help me decide?" |
| Don't know where to start | "I don't know where to start" |
| Just need somewhere to land | "I'm not ready to work on anything yet. I just need to talk." |

You don't need a perfect opening. Claude will ask for what it needs.

---

## File structure

```
liminalliving-job-search-waypoint/
├── SKILL.md                  # Skill definition, triggers, modes, quick reference
├── LICENSE                   # CC BY-NC 4.0
├── README.md                 # This file
└── references/
    └── protocol.md           # Full 9-step workflow, formulas, verb banks, QA checklist
```

---

## The framework at a glance

**The orienting question:** *"Why hire me for THIS role?"*

**The core insight:** The non-linear career is not a problem to solve. It is a story to
tell selectively.

**The nine steps:**
1. JD Deconstruction — keyword tiers, problem identification, gap analysis
2. Experience Mapping — metric hardening, sequential intake
3. Victory Bullet Formula — action verb + problem inherited + solution + trade-off + impact
4. Ownership Validation — every bullet answers "what would have failed without me?"
5. Summary & Competencies — track-aligned, 6-second scan, keyword-dense
6. Cover Letter — T-shape, 450 words max, no apologies for the arc
7. Employment History — date format, gap prevention, non-linear framing
8. QA Checklist — 160-char audit, keyword density, metric density, anti-AI writing check
9. Delivery — resume + cover letter + ATS report + 3 talking points

---

## Philosophy

> "Human capacity is not a variable to manage around. It is the system itself."

A waypoint is not a destination. The best resume in the world doesn't help someone
who can't make themselves send it. This tool holds both.

---

## License

CC BY-NC 4.0 — free to use and adapt with attribution. Not for commercial use without
permission. For licensing inquiries: marah.rosenberg+liminalskill@gmail.com

---

## About Liminal Living

Liminal Living is a practice of presence built on treating human capacity as the core
system rather than a variable to manage around. Work at the intersection of organizational
dynamics, grief literacy, and systems thinking.

[liminalliving.net](https://liminalliving.net)

---

## Support This Work

LiminalLiving — Job Search Waypoint is free for anyone navigating job loss. If it
helped you, consider buying the humans behind it a coffee.

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-☕-yellow)](https://www.buymeacoffee.com/LiminalLiving)
