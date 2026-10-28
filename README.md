# Apify skills by piotrv1001

Agent skills ([agentskills.io](https://agentskills.io/specification) format) that chain [Apify](https://apify.com) Actors into end-to-end research workflows. They work in Claude Code, Codex, Cursor, Gemini CLI and other agents that read `SKILL.md` files.

## Install

```bash
npx skills add piotrv1001/apify-skills
```

Pass `--list` to preview, or `-s <name>` to install one skill.

## Skills

| Skill | What it does |
|---|---|
| [`apify-cross-border-sourcing`](skills/apify-cross-border-sourcing/SKILL.md) | AliExpress product URL → reverse image search on 1688 and Alibaba.com → price ladder: retail vs. wholesale price, MOQ, supplier and match quality. |

## Requirements

- An [Apify account](https://apify.com) and the [Apify CLI](https://docs.apify.com/cli) (`npm install -g apify-cli`, then `apify login`), or an `APIFY_TOKEN` environment variable.

## Disclosure

The author built and maintains the Apify Actors these skills route to, and earns from their use. No affiliate or referral parameters are used.
