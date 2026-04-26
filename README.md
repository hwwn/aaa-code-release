<div align="center">

# `AAA Code`

**Anyone, Anywhere, Anytime** can code.

A full desktop client for Claude Code that wraps the Agent SDK<br>with everything the CLI should have had.

[![Website](https://img.shields.io/badge/Website-aaa--code.app-7c5bf5?style=for-the-badge&logo=vercel)](https://aaa-code.app/)
[![Download](https://img.shields.io/badge/Download-Latest_Release-7c5bf5?style=for-the-badge&logo=github)](https://github.com/hwwn/aaa-code-release/releases)
[![Pricing](https://img.shields.io/badge/Pricing-From_$5-7c5bf5?style=for-the-badge)](https://aaa-code.app/#pricing)
[![Platform](https://img.shields.io/badge/macOS_|_Windows_|_Linux-333?style=for-the-badge)](https://github.com/hwwn/aaa-code-release/releases)

</div>

<div align="center">
<br>
<img src="https://aaa-code.app/hero-screenshot.png" alt="AAA Code — multi-workspace conversation" width="680">
<br><br>
</div>

---

Claude Code is amazing. It's also kind of a pain.

You're stuck in a terminal. One project at a time. One working directory. You can't glance at what Claude is doing from your phone while you're on the couch. You can't fork a conversation that went sideways three messages ago.

So I built [claude-notify-everywhere](https://github.com/hwwn/claude-notify-everywhere) — at least my phone would buzz when Claude needed me. That helped. But I was still running back to the terminal, still fighting the single-CWD limitation, still losing conversation threads I wished I could rewind.

**It wasn't enough. So I built AAA Code.**

## What Makes It Different

### 🎮 Remote Control Your Projects

Start a task on your desktop, walk away. Check progress from your phone. Approve a permission request from the couch. Same WiFi or tunnel it through the internet — zero setup on the mobile side.

<div align="center">
<br>
<img src="https://aaa-code.app/remote-screenshot.png" alt="Remote access settings with Cloudflare tunnel" width="680">
<br><br>
</div>

<video src="https://aaa-code.app/aaa-remote-demo.mp4" width="100%" autoplay loop muted></video>

### 🔌 Bring Your Own LLM

Anthropic direct, DeepSeek, Zhipu, Kimi, MiniMax, AWS Bedrock, Google Vertex — or point at your own LiteLLM proxy. Configure once in **Settings → Providers**, then switch per session or globally for new chats. Your keys stay on-device; we never see your traffic.

<div align="center">
<br>
<img src="https://aaa-code.app/provider-screenshot.png" alt="Provider selection panel with Anthropic, DeepSeek, Bedrock and Vertex options" width="680">
<br><br>
</div>

<video src="https://aaa-code.app/aaa-provider-demo.mp4" width="100%" autoplay loop muted></video>

### 📂 Multiple Projects as Context

Claude Code locks you into one working directory. AAA Code lets you throw multiple project directories into the same conversation. *"Hey Claude, look at the API in repo A and the frontend in repo B and make them talk to each other."*

<div align="center">
<br>
<img src="https://aaa-code.app/workspace-screenshot.png" alt="Multi-workspace selection panel" width="680">
<br><br>
</div>

<video src="https://aaa-code.app/aaa-workspace-demo.mp4" width="100%" autoplay loop muted></video>

### 🌿 Fork Any Conversation Node

Three messages in, Claude takes a wrong turn. In the CLI, you're stuck restarting or awkwardly correcting course. In AAA Code, right-click any node in the session tree, fork it, and explore a different path. Keep the original. Branch like git, but for conversations.

<video src="https://aaa-code.app/aaa-demo-fork.mp4" width="100%" autoplay loop muted></video>

### ⏰ Scheduled Tasks _(VIP+)_

Daily standup reports, nightly refactors, weekly dependency checks — Claude does the work while you're asleep. Type `/schedule` in any session to put it on cron, or open the Scheduled tab to wire one up directly. Runs even when you walk away from the desk; results land in your session tree with a push notification on your phone.

<div align="center">
<br>
<img src="https://aaa-code.app/scheduled-screenshot.png" alt="Scheduled tasks panel with cron presets and run history" width="680">
<br><br>
</div>

<video src="https://aaa-code.app/aaa-scheduled-demo.mp4" width="100%" autoplay loop muted></video>

### 🌳 Session Management

See your entire conversation history at a glance. Resume any session right where you left off, or delete the ones you no longer need. Branches, forks, continuations — everything stays organized.

<div align="center">
<br>
<img src="https://aaa-code.app/session-screenshot.png" alt="Session history with resume and delete" width="680">
<br><br>
</div>

### ⚡ Full CLI Capabilities, in a GUI

Streaming responses, tool use, permission dialogs, MCP server integrations — it's all there. Use the same `/slash` commands from the CLI directly in the GUI. You're gaining a visual layer on top without losing anything.

<div align="center">
<br>
<img src="https://aaa-code.app/cli-screenshot.png" alt="CLI capabilities with slash commands in the GUI" width="680">
<br><br>
</div>

<video src="https://aaa-code.app/aaa-cli-demo.mp4" width="100%" autoplay loop muted></video>

### 🎨 Settings & Customization

One unified panel — theme (Purple / Orange / Rainbow, light or dark), default permission mode, providers, license activation, and remote-access tokens with copy-paste and QR. Everything you can configure lives in one place; no scattered preferences windows.

<div align="center">
<br>
<img src="https://aaa-code.app/theme-screenshot.png" alt="Unified Settings panel — theme picker, permission mode, providers, license, remote access" width="680">
<br><br>
</div>

<video src="https://aaa-code.app/aaa-theme-demo.mp4" width="100%" autoplay loop muted></video>

## Features

| Feature | Description |
|---------|-------------|
| **Multi-Workspace** | Multiple project directories in one conversation |
| **Multi-Provider** | Anthropic / DeepSeek / Zhipu / Kimi / MiniMax / Bedrock / Vertex / custom proxy |
| **Remote Access** | Phone/tablet access via local WiFi or Cloudflare tunnel |
| **Scheduled Tasks** | Run Claude on cron — daily, weekly, or one-shot (VIP+) |
| **Session Tree** | Visual conversation history — resume, delete, fork, and branch |
| **Permission Bridge** | Approve tool use and answer elicitations from any device |
| **Theme System** | Purple, Orange, Rainbow — light and dark mode |
| **Storage Management** | Monitor and clean up conversation history |
| **Cross-Platform** | macOS, Windows, Linux |

## Download

Grab the latest release from the **[Releases](https://github.com/hwwn/aaa-code-release/releases)** page.

| Platform | Files |
|----------|-------|
| macOS (Apple Silicon / Intel) | `.dmg` |
| Windows | `.msi` / `.exe` |
| Linux | `.AppImage` / `.deb` |

> [!NOTE]
> Releases are currently unsigned. On macOS, right-click the app and select **Open** on first launch. On Windows, click **More info** → **Run anyway**.

### Requirements

- [Node.js](https://nodejs.org/) 22+
- An [Anthropic API key](https://console.anthropic.com/) or Claude CLI already configured

## Roadmap

| When | What |
|------|------|
| **May — Early** | 🎙️ **Voice Input** — Talk to Claude instead of typing. Dictate prompts, describe bugs, think out loud — hands-free. |
| **May — Late** | 🧠 **Cross-Conversation Memory** — Claude remembers context across sessions. Preferences, decisions, and project history carry forward automatically. |
| **June** | 🗳️ **You decide** — [Open an issue](https://github.com/hwwn/aaa-code-release/issues) and tell us what you need most. |

## Pricing

<div align="center">
<br>
<img src="https://aaa-code.app/sponsor-preview.png" alt="AAA Code pricing dialog showing Member, VIP, and VVIP tiers" width="680">
<br><br>
</div>

AAA Code is free to try for 7 days. A one-time purchase unlocks continued use and lifetime updates.

| Tier | Price | What You Get |
|------|-------|-------------|
| **AAA Code Member** | $5 one-time | All core features + lifetime updates |
| **AAA Code VIP Member** | $10 one-time | Everything in Member + all premium features (Plugin System, Scheduled Tasks, Conversation Rename, Early Access) |
| **AAA Code VVIP Member** | $15 one-time | Everything in VIP + priority handling of feature requests and direct email support |

Pick a plan on the [**Pricing page**](https://aaa-code.app/#pricing). Payments are processed by Lemon Squeezy as Merchant of Record; your license key arrives by email and activates instantly in the app (Settings → License).

### Premium Features (VIP+)

- **Plugin System** — Use Claude Code skills (superpowers, frontend-design, code-review, etc.) directly via slash commands. Your installed CLI plugins just work.
- **Scheduled Tasks** — Run Claude on a cron schedule. Daily reports, nightly refactors, weekly check-ins — results land in your session tree with a phone notification.
- **Conversation Rename** — Double-click any session in the conversation tree to rename it.
- **Early Access** — New features before public release.

### VVIP Only

- **Priority Feature Requests** — Your feature requests and support tickets handled first.
- **Direct Email Support** — Reach us directly instead of going through the public issue tracker.

More premium features ship over time. Existing customers at each tier get everything automatically within their tier.

## Supported providers

Connect aaa-code to your preferred LLM backend in **Settings → Providers**.

| Provider | What you need | Zero-config path |
|---|---|---|
| Anthropic direct | API key or Claude Code CLI login | Run `claude login` once |
| DeepSeek / Zhipu / Kimi / MiniMax | API key from each provider | Settings → Providers → preset |
| Self-hosted proxy (LiteLLM, etc.) | Base URL + API key | Settings → Providers → custom |
| AWS Bedrock | AWS credentials + region | `~/.aws/credentials` auto-detected |
| Google Vertex | GCP project + ADC | `gcloud auth application-default login` |

See the full guide: https://aaa-code.app/guides/providers

## Issues & Feedback

Something broken? Have a feature idea? **[Open an issue](https://github.com/hwwn/aaa-code-release/issues)** — bug reports and feature requests are both welcome. This is the best way to shape what gets built next.

## License

Proprietary. All rights reserved.
