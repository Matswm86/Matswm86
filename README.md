## Hei. I build things with AI. Heck, it even wrote this! 

I got no computer-science degree and no team. I started from zero in early 2025
with an AI coding assistant, and everything below runs today. **Twenty-five public repositories,
many live sites.** Nobody has paid me for any of it yet, so read this as a workshop rather
than a shop. I have started on my python education and will take my first Azure certification in October and hopefully land a real job doing something AI related soon! 

I am most interested in the part where AI stops being a chatbot and becomes infrastructure:
agent harnesses, tool servers, retrieval over a real corpus, and systems honest enough to tell
you when they are wrong.
My personal interest of trading and physics/philosophy aligns well with this and I have several projects currently kept private dealing with these subjects as well as what you might find here...

---

### Start here

**[The Morning Brief](https://github.com/Matswm86/mwm-morning-brief)** · live at [brief.mwmai.no](https://brief.mwmai.no/)
A trading newspaper that typesets itself three times a day. It forecasts how *big* the session
will be, never which direction, and prints its own hit rate next to every call. A second page
reviews yesterday and last week against what the news wire actually ran, and says out loud when
the tape moved for reasons the headlines had nothing to do with. Python, no front-end framework.

**[TradingView Indicators](https://github.com/Matswm86/tradingview-indicators)**
Seven Pine Script v6 chart tools for intraday futures. The liquidity-sweep indicator has over 200
likes on TradingView, which is the only audience number here I did not have to qualify. Every
script ships its reasoning: what it refuses to trade and why, not just where it draws a line.
I also offer more advanced indicators for a monthly fee now via Whop. 

**[Pytor and PyQuest](https://github.com/Matswm86/pylearn)** · live at [pytor.mwmai.no](https://pytor.mwmai.no/)
Learn Python from absolute zero: 450 exercises across 9 topics, executing in your browser with
no install, plus a tutor that asks questions instead of handing over answers. The Android half
is a game with 231 questions and no typing, because writing Python on a phone keyboard is
miserable and pretending otherwise helps nobody.

**[VibeOS](https://github.com/Matswm86/vibeos)** · [vibeos.mwmai.no](https://vibeos.mwmai.no/)
A bootable AI-native Linux distribution: Ubuntu, KDE, a local model and an agent CLI, installed
in about ten minutes. **You choose the model and the provider.** It ships a small local model so
it works offline on first boot, and you can swap it, point it at your own hosted account, or
stay permanently offline. Not tied to one vendor.

---

### Tools and agents

| Repo | What it is |
|---|---|
| [vivarium-agent-skills](https://github.com/Matswm86/vivarium-agent-skills) | A sourced reference pack for building glass habitats, written as 52 plain-Markdown files any model can read. Every number a decision rests on carries a URL; gaps say UNVERIFIED instead of guessing |
| [mwm-harness](https://github.com/Matswm86/mwm-harness) | Work in progress: my own terminal agent harness for Qwen, Kimi and GLM |
| [glm-free-claude-code](https://github.com/Matswm86/glm-free-claude-code) | Run a free GLM API behind Claude Code, or offload bulk work off a paid session |
| [fenrir-boss](https://github.com/Matswm86/fenrir-boss) | A simulated workplace that trains you: an AI boss who assigns tickets, reviews your code and never writes it |
| [oso-sync](https://github.com/Matswm86/oso-sync) | Obsidian plus Syncthing plus Ollama: an always-on personal AI notes stack with nothing in the cloud |

### Apps and games for Android

Every one is free, with no ads, no in-app purchases and no analytics. Several ask for no
internet permission at all.

| Repo | What it is |
|---|---|
| [mwm-reader](https://github.com/Matswm86/mwm-reader) | Ad-free offline reader: PDF, EPUB, Office, and code in 60+ languages |
| [mwm-music](https://github.com/Matswm86/mwm-music) | A quiet Winamp-style player for local files |
| [mwm-chess](https://github.com/Matswm86/mwm-chess) | Beginner-friendly chess that shows every legal move |
| [mwm-cloud](https://github.com/Matswm86/mwm-cloud) | Backs your phone up to storage you own, then proves the backup actually worked |
| [pm98-android](https://github.com/Matswm86/pm98-android) | Premier Manager 98 rebuilt from the original game's own files, full 1997-98 database |
| [pcleague](https://github.com/Matswm86/pcleague) · [USM2](https://github.com/Matswm86/USM2) · [sar2007-android](https://github.com/Matswm86/sar2007-android) | More rebuilds of 1990s games from their own data, not from memory |
| [jezzball](https://github.com/Matswm86/jezzball) · [ball-connect](https://github.com/Matswm86/ball-connect) · [tile-explorer](https://github.com/Matswm86/tile-explorer) | Small puzzle games in Godot 4 |
| [wiggle-and-think](https://github.com/Matswm86/wiggle-and-think) | Movement breaks for children aged 4 to 7, honest about what the research does and does not show |

### And one small one

**[manual_codes](https://github.com/Matswm86/manual_codes)** is the code I wrote by hand, myself,
without an assistant. It is currently a short list. I am keeping it separate on purpose, because the
difference between directing a build and writing it matters and I would rather label it than
blur it.

---

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

[mrmaxwilliam@gmail.com](mailto:mrmaxwilliam@gmail.com) · [mwmai.no](https://mwmai.no/)

Open to consulting on agent harnesses, MCP tool servers and retrieval systems, and to back-office
automation work for small firms.
