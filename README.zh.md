# AI 用量仪表

[English](README.md) · [한국어](README.ko.md) · [日本語](README.ja.md) · **简体中文**

一个始终置顶的 Windows 小工具：在你用 Claude Code 做到一半触顶之前，**估算**剩余用量并一直显示在屏幕角落。

![演示](demo_zh.gif)

## 下载（7 天免费试用）

**[⬇ 下载 AIUsageGauge.exe](../../releases/latest/download/AIUsageGauge.exe)** — Windows 11（Windows 10 尚在测试），无需管理员权限

试用结束后一次买断，约 $5（₩6,900）— **[购买许可证](https://aivex.lemonsqueezy.com/checkout/buy/e78a9038-fcea-45ee-848a-5a87f3def1a9)**。不是订阅。

> 安装包暂时没有代码签名，首次运行可能出现「Windows 已保护你的电脑」，点 **更多信息 → 仍要运行** 即可。

## 功能

- **看颜色就行。** 5 小时窗口和最近 7 天用量：绿色充足、黄色注意、红色快用完
- **从真实限额中学习。** 触顶一次后按当时用量更准确地估算剩余，并提示按当前速度何时用完
- **多个 AI 分标签。** 使用 Codex、Gemini CLI、Antigravity 会自动出现标签
- **找出浪费的用量。** 找出过长的对话，并复制摘要方便在新对话中继续
- 双击缩成一行、深色/浅色主题、4 档字号、简体中文·English·日本語·한국어

## 隐私

- 只读取本机 AI 工具留下的日志（Claude Code：`~/.claude/projects`）
- 不读取登录信息和令牌；对话内容不出本机（联网仅用于验证许可证）
- 剩余用量是**估算**，不是官方数据

与 Anthropic、OpenAI、Google 无关的个人开发非官方工具。欢迎在 [Issues](../../issues) 反馈。
