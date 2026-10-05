## Hei. I build things with AI. Heck, it even wrote this! 

I got no computer-science degree and no team. I started from zero in early 2025
with an AI coding assistant, and everything below runs today. **Thirty-one public repositories,
many live sites.** Nobody has paid me for any of it yet, so read this as a workshop rather
than a shop. I have started on my Python education, will take my first Azure certification (AI-901) in October, and hopefully land a real job doing something AI related soon! 

I am most interested in the part where AI stops being a chatbot and becomes infrastructure:
agent harnesses, tool servers, retrieval over a real corpus, and systems honest enough to tell
you when they are wrong.
My personal interest of trading and physics/philosophy aligns well with this and I have several projects currently kept private dealing with these subjects as well as what you might find here...

---

### Start here

**[The Morning Brief](https://github.com/Matswm86/mwm-morning-brief)** · live at [brief.mwmai.no](https://brief.mwmai.no/)
A trading newspaper for MNQ and MGC futures that typesets itself through the day, now in its
third broadsheet edition: rotating headlines, masthead ears and a Funny Pages strip. It forecasts
how *big* the session will be, never which direction, and prints its own hit rate next to every
call. A 15:25 Oslo regime lens and an intraday read validated on 252 held-out sessions sit beside
a Strategy Desk that reviews yesterday and last week against what the news wire actually ran, and
says out loud when the tape moved for reasons the headlines had nothing to do with. Python, no
front-end framework.

**[TradingView Indicators](https://github.com/Matswm86/tradingview-indicators)**
Seven Pine Script v6 chart tools for intraday futures. The liquidity-sweep indicator has over 200
likes on TradingView, which is the only audience number here I did not have to qualify. Every
script ships its reasoning: what it refuses to trade and why, not just where it draws a line.
I also offer more advanced indicators for a monthly fee now via Whop. 

**[Pytor and PyQuest](https://github.com/Matswm86/pylearn)** · live at [pytor.mwmai.no](https://pytor.mwmai.no/)
Learn Python and AI engineering from absolute zero: 450 exercises across 9 topics, executing in
your browser with no install, plus a tutor that asks questions instead of handing over answers.
The site got a new navy-and-teal look with dark mode, and a 74-question AI-901 drill in real exam
format. The Android half, PyQuest, now lives in the same repo: 325 questions across 9 tiers and
no typing, including 94 AI-901 exam questions with choose-N answers, because writing Python on a
phone keyboard is miserable and pretending otherwise helps nobody.

**[Timber Valley](https://github.com/Matswm86/timber-valley)** · [download the APK](https://github.com/Matswm86/timber-valley/releases/download/latest/timber-valley.apk)
A calm 3D lumber mill for Android: chop trees, saw planks, sell them at a market by the road and
spend the money on machines, workers, conveyor belts and a crane-fed mega sawmill, across three
valleys (Home Valley, Birch Bend, Maple Highlands). It is the fun part of those "idle arcade"
phone ads without the ad-supported game around it: no ads, no in-app purchases, no timers, no
analytics. Godot 4, built by GitHub Actions on every push.

---

### Tools and agents

| Repo | What it is |
|---|---|
| [vivarium-agent-skills](https://github.com/Matswm86/vivarium-agent-skills) | A sourced reference pack for building glass habitats, written as 56 plain-Markdown files any model can read. Every number a decision rests on carries a URL; gaps say UNVERIFIED instead of guessing |
| [vibeos](https://github.com/Matswm86/vibeos) | Work in progress: a bootable AI-native Linux distribution (Ubuntu, KDE, a local model and an agent CLI) where you choose the model and the provider. No public ISO yet; you build it from the repo |
| [mwm-harness](https://github.com/Matswm86/mwm-harness) | Work in progress: my own agent harness for Qwen, Kimi and GLM, with a terminal prompt, a local browser panel, permissions, a sandbox, hooks, MCP and subagents |
| [glm-free-claude-code](https://github.com/Matswm86/glm-free-claude-code) | Run free GLM 5.2 behind Claude Code: a full GLM session, one-shot offloads from a paid session, or a whole task handed to a headless GLM agent |
| [fenrir-boss](https://github.com/Matswm86/fenrir-boss) | A simulated workplace that trains you: an AI boss who assigns tickets, reviews your code and never writes it |
| [oso-sync](https://github.com/Matswm86/oso-sync) | Obsidian plus Syncthing plus Ollama: write a question in a synced note and a small Python responder appends the answer in place. Groq first, local Ollama as the fallback, or fully local if you skip the key |

### Apps and games for Android

Every one is free, with no ads, no in-app purchases and no analytics. Several ask for no
internet permission at all.

| Repo | What it is |
|---|---|
| [mwm-reader](https://github.com/Matswm86/mwm-reader) | Ad-free offline reader: PDF, EPUB, Office, and code in about 80 file types |
| [mwm-music](https://github.com/Matswm86/mwm-music) | A quiet Winamp-style player for local files |
| [mwm-chess](https://github.com/Matswm86/mwm-chess) | Beginner-friendly 3D chess that shows every legal move. New: medieval silver-and-gold pieces that glide between squares, and online play with a friend via a 4-letter game code |
| [mwm-compass](https://github.com/Matswm86/mwm-compass) | New: a plain, precise retro compass with magnetic or true north, a bearing mark and a bubble level. No internet permission |
| [mwm-cloud](https://github.com/Matswm86/mwm-cloud) | Backs your phone up to storage you own, then proves the backup actually worked |
| [pm98-android](https://github.com/Matswm86/pm98-android) | Premier Manager 98 rebuilt from the original game's own files, full 1997-98 database |
| [pcleague](https://github.com/Matswm86/pcleague) · [USM2](https://github.com/Matswm86/USM2) · [sar2007-android](https://github.com/Matswm86/sar2007-android) | More rebuilds of older games from their own data, not from memory. sar2007-android is still at the stage of unpacking the game's files |
| [fishy](https://github.com/Matswm86/fishy) | The 2003 Flash game Fishy on Android, with its original art, music and rules: eat the smaller fish, stay away from the bigger ones |
| [krypton-egg](https://github.com/Matswm86/krypton-egg) | Krypton Egg, the Breakout game from the 1996 C2V Games Suite CD, on Android: all 100 levels, the art and the sound come off the original disc |
| [jezzball](https://github.com/Matswm86/jezzball) · [ball-connect](https://github.com/Matswm86/ball-connect) · [tile-explorer](https://github.com/Matswm86/tile-explorer) | Small puzzle games in Godot 4. Tile Explorer just moved onto a walnut table with a felt mat |
| [water-sort](https://github.com/Matswm86/water-sort) | A colour-sorting water puzzle in Godot 4. Endless levels, each checked solvable by a built-in solver before you see it, plus unlimited undo. No internet permission |
| [wiggle-and-think](https://github.com/Matswm86/wiggle-and-think) | Movement breaks for children aged 4 to 7, live at [wiggle.mwmai.no](https://wiggle.mwmai.no/), honest about what the research does and does not show |

### And one small one

**[manual_codes](https://github.com/Matswm86/manual_codes)** is the code I wrote by hand, myself,
without an assistant. It is currently a short list. I am keeping it separate on purpose, because the
difference between directing a build and writing it matters and I would rather label it than
blur it.

---

### How the system is engineered

AI agents write most of the code. I design the architecture, set the rules they work under,
review what comes back and decide what ships. The part I own looks like this (counts measured
2026-09-29):

| Area | What is in place |
|---|---|
| **Architecture** | About 50 projects, one repository each, around a shared core of MCP tool servers, Qdrant and Neo4j. Trading and creative work are kept apart by a guard that blocks one domain's tools in the other's sessions. Shared config has one canonical copy; syncing it into repos is an explicit step that refuses to run mid-commit |
| **Guardrails on the AI** | Around 30 Claude Code hooks at every point of an agent's turn: they block writes outside the workspace, warn before destructive shell commands and enforce 56 written rules. A change of 50+ lines to core code starts an independent reviewer agent; claims about third-party products get checked against vendor docs before I read them |
| **Separation of duties** | 32 specialist subagents split into builders and auditors. The agent that writes a backtest engine never grades it; one auditor checks the fill logic, another the results. "Tests pass" counts only with the pasted output |
| **Security** | Secret scanning (detect-secrets) on every commit in 13 repos, pip-audit in CI, strict Content-Security-Policy on the public sites. AI tools have read-only access to the trading account and no path to place an order. A prompt-injection honeypot runs weekly against a fixed pass floor |
| **CI/CD and testing** | 21 repos build and test in GitHub Actions, including every Android APK. Pre-commit runs ruff, formatting and secret checks, never skipped. Over 250 test files across the core system and the trading platform |
| **Research discipline** | Pass/fail bars are written before a backtest runs, and engines are audited for fills the market would never give you. 56 failed ideas sit in a register so nobody re-runs them hoping for luck. Anything that fails quietly must leave a tag, a counter and a log line |

### How I work

- **Measure, then claim.** Numbers in my repos carry the date they were measured. When something
  is unverified it says UNVERIFIED rather than getting a confident sentence.
- **Publish the negative results.** Most research ideas I test come back indistinguishable from
  noise, and those get written up the same as the ones that work. A study of prop-firm trading
  I ran concluded that a zero-skill trader passes the evaluation 22 to 26% of the time, which
  is not a flattering finding for the thing I was building.
- **No performance theatre.** No backtest screenshots without the fill assumptions, no profit
  claims, no "AI-powered" on something that calls an API once.

### Reach me

[mrmaxwilliam@gmail.com](mailto:mrmaxwilliam@gmail.com) · [mwmai.no](https://mwmai.no/), which now
doubles as a catalogue of every live site, Android app and public repo.

Open to consulting on agent harnesses, MCP tool servers and retrieval systems, and to back-office
automation work for small firms.
