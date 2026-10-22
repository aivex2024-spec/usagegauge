# AI Usage Gauge

**English** · [한국어](README.ko.md) · [日本語](README.ja.md) · [简体中文](README.zh.md)

A tiny always-on-top Windows widget that shows an **estimate** of how much of your Claude Code usage is left — before you hit the limit in the middle of a task.

![demo](demo.gif)

## Download (free 7-day trial)

**[⬇ Download AIUsageGauge.exe](../../releases/latest/download/AIUsageGauge.exe)** — Windows 11 (Windows 10 not tested yet), no admin rights needed.

After the trial: one-time purchase, about $5 (₩6,900) — **[Buy a license](https://aivex.lemonsqueezy.com/checkout/buy/e78a9038-fcea-45ee-848a-5a87f3def1a9)**. No subscription.

> The installer isn't code-signed yet, so Windows SmartScreen may show "Windows protected your PC" on first run. Click **More info → Run anyway**.

## What it does

| | |
|---|---|
| ![](01_plenty_1280x800.png) | **Just watch the color.** Green is fine, yellow is caution, red is almost out — for the 5-hour window and the last 7 days. |
| ![](03_almost_out_1280x800.png) | **Learns your real limit.** Once you've hit a limit, it uses that amount to estimate what's left more accurately, and tells you when you'll run out at this pace. |
| ![](06_tabs_1280x800.png) | **All your AI tools in tabs.** Codex, Gemini CLI and Antigravity get their own tab if you use them. |
| ![](07_saver_1280x800.png) | **Finds where usage leaks.** Spots overly long chats and copies a summary so you can continue in a fresh one. |

Also: double-click to shrink it to one line, dark/light theme, four text sizes, sharp on mixed-DPI monitors, and an English / 日本語 / 简体中文 / 한국어 UI that follows your Windows language.

## Privacy

- It reads only the logs AI coding tools already leave on your PC (Claude Code: `~/.claude/projects`).
- It never reads your login or tokens, and never calls private endpoints.
- Conversations never leave your PC. The internet is used only to check the license.
- The remaining amount is an **estimate**, not an official number.

## FAQ

**Is this official?** No. It's an unofficial tool by an independent developer, not affiliated with Anthropic, OpenAI or Google.

**How accurate is it?** Until you hit a limit once, it compares you with your own busiest 5 hours / 7 days ("headroom"). After a limit hit, it uses that real amount.

**How many PCs?** One license works on up to 3 PCs.

**Uninstall?** Windows Settings → Apps → AI Usage Gauge → Uninstall.

---
This repository holds the download and documentation only. Feedback and bug reports are welcome in [Issues](../../issues).
