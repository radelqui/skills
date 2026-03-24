---
name: claw-setup-configuration
description: Configure OpenClaw AI assistant â€” model chain, providers, SOUL.md, cron, and gateway settings
version: 1.0.0
author: radelqui
tags: [openclaw, setup, configuration, ai-agents, productivity]
---

# claw-setup-configuration

Guided configuration assistant for OpenClaw AI assistant setup and management.

## Usage

```
/claw-setup-configuration [what you want to configure]
```

## What this does

Helps you configure and manage an OpenClaw installation:
- Model chain setup (primary + fallback providers)
- SOUL.md, USER.md, and IDENTITY.md workspace files
- Provider credentials (Anthropic, OpenAI, OpenRouter, etc.)
- Gateway, cron, and webhook configuration
- Agent memory and context settings

## When to use this

- First-time OpenClaw setup on a VPS or local machine
- Switching model providers or adding fallback models
- Configuring agent personality and workspace files
- Troubleshooting gateway or provider connection issues
- Reviewing and auditing current configuration

## How it works

1. Reads your current OpenClaw configuration (if it exists)
2. Guides you through the necessary changes step by step
3. Validates settings and checks for common mistakes
4. Applies changes with confirmation at each step

## Requirements

- OpenClaw installed (see official installation docs)
- API keys for your chosen providers

## Install via ClawHub

```bash
clawhub install radelqui/claw-setup-configuration
```
