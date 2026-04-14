# AAA Code

Claude Code is amazing. It's also kind of a pain.

You're stuck in a terminal. One project at a time. One working directory. You can't glance at what Claude is doing from your phone while you're on the couch. You can't fork a conversation that went sideways three messages ago. You can't throw two repos at it and say "figure this out together."

So I built [claude-notify-everywhere](https://github.com/hwwn/claude-notify-everywhere) — at least my phone would buzz when Claude needed me. That helped. But I was still running back to the terminal, still fighting the single-CWD limitation, still losing conversation threads I wished I could rewind.

It wasn't enough.

So I built **AAA Code** — AKA **Anyone, Anywhere, Anytime** can code.

A full desktop client that wraps the Claude Agent SDK with everything I wished the CLI had. And then some.

## What Makes It Different

**Use your phone. No apps to install.**

Open a URL on your phone, tablet, whatever — your Claude sessions are right there. Watch the conversation stream in real-time. Send messages. Approve permissions. All from the browser. Same WiFi or tunnel it through the internet. Zero setup on the mobile side.

**Multiple projects as context. Not just one CWD.**

Claude Code locks you into one working directory. AAA Code lets you throw multiple project directories into the same conversation. "Hey Claude, look at the API in repo A and the frontend in repo B and make them talk to each other." Done.

**Fork any conversation node.**

Three messages into a conversation, Claude takes a wrong turn. In the CLI, you're stuck restarting or awkwardly correcting course. In AAA Code, right-click any node in the session tree, fork it, and explore a different path. Keep the original. Branch like git, but for conversations.

**Full Claude CLI capabilities, wrapped in a GUI.**

Streaming responses, tool use, permission dialogs, MCP server integrations — it's all there. You're not losing anything from the CLI. You're gaining a visual layer on top.

## Features

- **Multi-Workspace** — Multiple project directories in one conversation
- **Remote Access** — Phone/tablet access via local WiFi or Cloudflare tunnel, no app install needed
- **Session Tree** — Visual conversation history with fork/branch support
- **Permission Bridge** — Approve tool use and answer elicitations from any device
- **Theme System** — Purple, Orange, Rainbow. Light and dark mode
- **Storage Management** — Monitor and clean up conversation history
- **Cross-Platform** — macOS, Windows, Linux

## Download

Grab the latest release for your platform from the [Releases](https://github.com/hwwn/aaa-code-release/releases) page.

| Platform | File |
|----------|------|
| macOS (Apple Silicon) | `.dmg` |
| macOS (Intel) | `.dmg` |
| Windows | `.msi` / `.exe` |
| Linux | `.AppImage` / `.deb` |

> Releases are currently unsigned. On macOS, right-click the app and select "Open" on first launch. On Windows, click "More info" → "Run anyway."

## Requirements

- [Node.js](https://nodejs.org/) 22+
- An [Anthropic API key](https://console.anthropic.com/) or Claude CLI already configured

## Sponsor

AAA Code is free. All features, no paywalls (for now).

If it saves you time or sanity, consider [sponsoring](https://github.com/sponsors/hwwn). Sponsors get a Pro license key that unlocks future premium features as they ship.

| Tier | Monthly | What You Get |
|------|---------|-------------|
| Supporter | $5 | Pro License Key |
| Backer | $10 | Pro License Key + Credits on the site |

## Issues & Feedback

Something broken? Something missing? [Open an issue](https://github.com/hwwn/aaa-code-release/issues).

## License

Proprietary. All rights reserved.
