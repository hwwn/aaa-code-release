# Security Policy

Thanks for taking the time to help keep AAA Code users safe.

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Use GitHub's private vulnerability reporting flow instead:

➡️ **[Report a vulnerability](https://github.com/hwwn/aaa-code-release/security/advisories/new)**

This opens a private channel between you and the maintainers; nothing is public until we agree on a fix and a coordinated disclosure.

If for some reason that page is unavailable, you can also email **hwwn@live.com** with `[AAA Code Security]` in the subject. Please mention your GitHub handle so we can credit you in the advisory if you'd like.

## What to include

The more of this we have, the faster we can confirm and fix:

- A clear description of the issue and its impact (what can an attacker do?)
- The affected version(s) — see the `app.version` shown in `Settings → About`, or the release tag you downloaded
- Your operating system and version
- Reproduction steps, ideally with a minimal proof of concept
- Logs, screenshots, or screen recordings if they help
- Whether you've shared this with anyone else, and any disclosure deadline you have in mind

## What you can expect from us

- **Acknowledgement** within **3 business days** of your report.
- **Initial assessment** (confirmed / not-a-vuln / need more info) within **7 business days**.
- A best-effort fix timeline once the issue is confirmed. Critical issues that put user data, machines, or API keys at risk are prioritized over everything else.
- A published [GitHub Security Advisory](https://github.com/hwwn/aaa-code-release/security/advisories) once a fix ships, crediting you (unless you'd rather stay anonymous).

This is a small indie project, so timelines are best-effort, not contractual — but you will hear back.

## Supported versions

Only the **latest release** receives security fixes. Older versions are not patched; please update via the [Releases page](https://github.com/hwwn/aaa-code-release/releases).

## Scope

In scope:

- The AAA Code desktop client (macOS / Windows / Linux binaries published in this repo's Releases)
- The remote-access HTTP/WebSocket surface exposed by the desktop client (LAN URL, Cloudflare tunnel)
- The website at https://aaa-code.app and any code under `https://github.com/hwwn/aaa-code-site`

Out of scope:

- Vulnerabilities in upstream dependencies — please report those to the upstream project (we'll happily relay if you're stuck)
- Issues that require physical access to an already-unlocked machine
- Social-engineering attacks, missing best-practice headers without a concrete impact, denial of service via unbounded resource consumption when the attacker already has full local access, or theoretical issues without a working PoC
- Findings against forks of AAA Code that we do not maintain

## A note on user data

AAA Code talks directly to your chosen LLM provider using your own API key. Your prompts, code, and conversations stay on your device — they never reach our servers. The app collects no telemetry. If you find a bug that breaks this property in any way, **please report it under this policy** rather than opening a public issue; that's exactly the kind of finding we want to handle privately.

## Safe-harbor

We will not take legal action against, or ask GitHub to suspend, anyone who:

- Makes a good-faith effort to follow this policy
- Avoids privacy violations, data destruction, and service degradation while researching
- Gives us a reasonable window to fix the issue before public disclosure

Thank you. ♡
