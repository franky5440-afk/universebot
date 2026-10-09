# Universe Bot

**One coordinator, a whole AI team, all on your computer.**

[繁體中文](README.zh-TW.md) · [Website](https://universebot.si/en/) · [Download](https://universebot.si/en/download/) · [Docs](https://universebot.si/en/docs/install/) · [FAQ](https://universebot.si/en/docs/faq/)

Universe Bot is a desktop app for Mac and Linux that turns AI agents into contacts in a chat app. Tell the coordinator what you need and it hands the work to teammates. They message each other and report back, you see every step, and you can jump in at any time.

It runs on the Claude, ChatGPT or Gemini account you already signed in to, or on an API key of your own. Everything runs on your computer.

> **Free during the public beta — testers wanted.** Model costs depend on the services you use (your subscription quota or your API bill). See [Feedback](#feedback) for how to report problems.

![Delegating work: the coordinator messages a teammate and the teammate reports back](https://universebot.si/screenshots/en/delegation.webp)

## What it does

- **Every agent is its own person.** Name, avatar, personality, rules and memory are set per agent.
- **Every agent picks its own model.** Send small chores to a cheap model and hard problems to a strong one. Mix Claude, ChatGPT (Codex) and Gemini subscriptions with OpenAI-compatible API keys (for example OpenRouter).
- **Delegating is just messaging.** The coordinator messages work to teammates instead of waiting on them. Several teammates can work at once.
- **See the usage, clear the session.** Each agent has its own usage panel. When a chat gets long or expensive, press Clear session; memory, personality and rules stay put.
- **Routines.** Hand out work automatically every day, week or month. A missed run catches up when your computer is back on.
- **Browses for you, hands over when stuck.** An agent can open its own browser. When a sign-in or verification step needs a human, it asks you to take over.
- **Talk to the coordinator from your phone** over Telegram or iMessage. It is the same conversation you see on the desktop.
- **You decide the permissions.** Four permission levels per agent, from chat only to reading and writing the work folder. Web search can only be turned on by you, on screen.

| | |
|---|---|
| ![Picking a model per agent](https://universebot.si/screenshots/en/models.webp) | ![Per-agent usage panel](https://universebot.si/screenshots/en/usage.webp) |
| ![Permission levels](https://universebot.si/screenshots/en/permissions.webp) | ![Telegram and iMessage settings](https://universebot.si/screenshots/en/messaging.webp) |

## Download

Current version **0.2.9**.

| Platform | File |
|---|---|
| Mac, Apple silicon (notarized) | [UniverseBot-arm64.dmg](https://download.universebot.si/latest/UniverseBot-arm64.dmg) |
| Mac, Intel (notarized) | [UniverseBot-x64.dmg](https://download.universebot.si/latest/UniverseBot-x64.dmg) |
| Linux x64 (AppImage) | [UniverseBot-x86_64.AppImage](https://download.universebot.si/latest/UniverseBot-x86_64.AppImage) |

Requirements: macOS 13 or later, or Linux x64 with a desktop environment. You need at least one of: Claude Code, Codex CLI or Gemini CLI signed in to your own account, or an API key of your own. The app's start screen checks what is missing and gives you the install commands. Full steps: [installation guide](https://universebot.si/en/docs/install/).

## Feedback

This is a public beta and feedback is the whole point. Pick whatever is easiest:

- **[Open an issue](../../issues/new/choose)** on this repository (bug report or suggestion).
- **Email** support@universebot.si if you prefer to write privately.

Please do **not** paste API keys, passwords, pairing codes or private conversations into an issue. Issues here are public.

## About this repository

This repository holds the public description, release notes and issue tracker for Universe Bot. The app's source code is not published here.

Universe Bot is an independent project by Frank Lin. It is not affiliated with Anthropic, OpenAI or Google, and it is not the Discord bot of the same name.

© Frank Lin. All rights reserved. [Privacy](https://universebot.si/en/privacy/)
