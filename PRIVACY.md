# Privacy Policy — AI Usage Gauge

Last updated: 2026-10-23

AI Usage Gauge ("the app") is a Windows desktop widget by AIvEX. This policy explains what the app reads and what, if anything, leaves your PC.

## What the app reads (stays on your PC)
- Usage logs that AI coding tools already save on your PC (for example Claude Code: `~/.claude/projects`; Codex, Gemini CLI, Antigravity and Cursor local files). Only counts and timestamps are used to draw the gauge.
- If you turn on "Claude Code official numbers", the app adds a small status-line script to `~/.claude/settings.json`. Claude Code passes its usage percentages to that script, which saves them to a local file. You can turn this off at any time and your previous setting is restored.
- The app never reads your login, passwords or tokens, and never sends your conversations anywhere.

## What leaves your PC
- **License check only.** When you enter a license key, the app sends the key and your PC's name to Lemon Squeezy (our payment and license provider) to activate it, and later the key and an activation ID to confirm it is still valid. Lemon Squeezy's privacy policy: https://www.lemonsqueezy.com/privacy
- **Purchases** happen on Lemon Squeezy's checkout page, not inside the app. We receive the order details Lemon Squeezy provides (such as email address) to deliver and support your license.
- **Feedback** (optional): the feedback button opens a GitHub issue page pre-filled with the app version, edition, language and Windows version. Nothing is sent unless you submit it yourself.

The app has no ads, analytics or tracking.

## Data stored on your PC
Settings, license state and the official-number file are saved under `%APPDATA%\AIUsageGauge` (Store version: the app's private storage and `~/.aiusagegauge`). Uninstalling removes the app's settings (the installer version asks first). The Store version leaves the small `~/.aiusagegauge` folder, which you can delete; turn the official-number connection off before uninstalling to restore your status line.

## Contact
Questions or deletion requests: https://github.com/aivex2024-spec/usagegauge/issues or aivex2024@gmail.com
