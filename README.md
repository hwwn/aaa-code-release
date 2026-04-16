<div align="center">

# `AAA Code`

**Anyone, Anywhere, Anytime** can code.

A full desktop client for Claude Code that wraps the Agent SDK<br>with everything the CLI should have had.

[![Website](https://img.shields.io/badge/Website-aaa--code--site.vercel.app-7c5bf5?style=for-the-badge&logo=vercel)](https://aaa-code-site.vercel.app/)
[![Download](https://img.shields.io/badge/Download-Latest_Release-7c5bf5?style=for-the-badge&logo=github)](https://github.com/hwwn/aaa-code-release/releases)
[![Sponsor](https://img.shields.io/badge/Sponsor-hwwn-ea4aaa?style=for-the-badge&logo=githubsponsors)](https://github.com/sponsors/hwwn)
[![Platform](https://img.shields.io/badge/macOS_|_Windows_|_Linux-333?style=for-the-badge)](https://github.com/hwwn/aaa-code-release/releases)

</div>

<div align="center">
<br>
<img src="https://aaa-code-site.vercel.app/hero-screenshot.png" alt="AAA Code — multi-workspace conversation" width="680">
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
<img src="https://aaa-code-site.vercel.app/remote-screenshot.png" alt="Remote access settings with Cloudflare tunnel" width="680">
<br><br>
</div>

<video src="https://aaa-code-site.vercel.app/aaa-remote-demo.mp4" width="100%" autoplay loop muted></video>

### 📂 Multiple Projects as Context

Claude Code locks you into one working directory. AAA Code lets you throw multiple project directories into the same conversation. *"Hey Claude, look at the API in repo A and the frontend in repo B and make them talk to each other."*

<div align="center">
<br>
<img src="https://aaa-code-site.vercel.app/workspace-screenshot.png" alt="Multi-workspace selection panel" width="680">
<br><br>
</div>

<video src="https://aaa-code-site.vercel.app/aaa-workspace-demo.mp4" width="100%" autoplay loop muted></video>

### 🌿 Fork Any Conversation Node

Three messages in, Claude takes a wrong turn. In the CLI, you're stuck restarting or awkwardly correcting course. In AAA Code, right-click any node in the session tree, fork it, and explore a different path. Keep the original. Branch like git, but for conversations.

<video src="https://aaa-code-site.vercel.app/aaa-demo-fork.mp4" width="100%" autoplay loop muted></video>

### 🌳 Session Management

See your entire conversation history at a glance. Resume any session right where you left off, or delete the ones you no longer need. Branches, forks, continuations — everything stays organized.

<div align="center">
<br>
<img src="https://aaa-code-site.vercel.app/session-screenshot.png" alt="Session history with resume and delete" width="680">
<br><br>
</div>

### ⚡ Full CLI Capabilities, in a GUI

Streaming responses, tool use, permission dialogs, MCP server integrations — it's all there. Use the same `/slash` commands from the CLI directly in the GUI. You're gaining a visual layer on top without losing anything.

<div align="center">
<br>
<img src="https://aaa-code-site.vercel.app/cli-screenshot.png" alt="CLI capabilities with slash commands in the GUI" width="680">
<br><br>
</div>

<video src="https://aaa-code-site.vercel.app/aaa-cli-demo.mp4" width="100%" autoplay loop muted></video>

### 🎨 Themes & Customization

Switch between multiple visual themes to personalize your workspace. Dark, light, and everything in between.

<div align="center">
<br>
<img src="https://aaa-code-site.vercel.app/theme-screenshot.png" alt="Theme and settings panel with light mode" width="680">
<br><br>
</div>

<video src="https://aaa-code-site.vercel.app/aaa-theme-demo.mp4" width="100%" autoplay loop muted></video>

## Features

| Feature | Description |
|---------|-------------|
| **Multi-Workspace** | Multiple project directories in one conversation |
| **Remote Access** | Phone/tablet access via local WiFi or Cloudflare tunnel |
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

## Pro Features

Sponsors get a Pro license key that unlocks:

- **Plugin System** — Use Claude Code skills (superpowers, frontend-design, code-review, etc.) directly via slash commands. Your installed CLI plugins just work.
- **Conversation Rename** — Double-click any session in the conversation tree to rename it.
- **Priority Support** — Issues and feature requests handled first.
- **Early Access** — New features before public release.

More Pro features ship over time. Existing sponsors get everything automatically.

## Sponsor

<div align="center">
<br>
<img src="https://aaa-code-site.vercel.app/sponsor-preview.png" alt="AAA Code sponsor dialog" width="680">
<br><br>
</div>

AAA Code is free to use. Core features have no paywalls.

If it saves you time or sanity, consider a one-time [sponsorship](https://github.com/sponsors/hwwn). You'll get a permanent Pro license key.

| Tier | Price | What You Get |
|------|-------|-------------|
| **Supporter** | $5 one-time | Pro License Key |
| **Backer** | $10 one-time | Pro License Key + Credits on the site |
| **Champion** | $15 one-time | Pro License Key + Credits + Priority Issues |

## Issues & Feedback

Something broken? Have a feature idea? **[Open an issue](https://github.com/hwwn/aaa-code-release/issues)** — bug reports and feature requests are both welcome. This is the best way to shape what gets built next.

## License

Proprietary. All rights reserved.
