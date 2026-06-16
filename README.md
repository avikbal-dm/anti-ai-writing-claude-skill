![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Type](https://img.shields.io/badge/Claude-Skill-da7756)

# Anti-AI Writing Style, the Humanizer

Humanize AI writing so it reads like a real person wrote it.

A practitioner's writing-style ruleset and editor for Claude, by [Avik Bal](https://github.com/avikbal-dm). It turns flat, generic model output into clear, specific, original content with a genuine voice. It removes the AI tells, forces real specificity, asks you for the inputs only you have, and never fabricates facts, data, or examples.

## What's in this repo

| File | What it is |
|------|------------|
| `anti-ai-writing-style-avikbal.skill` | The installable skill bundle. Upload this to Claude. |
| `anti-ai-writing-style-avikbal-SKILL.md` | The full ruleset, readable here in the browser. |
| `anti-ai-writing-style-avikbal-README.md` | The long-form guide: workflow, personalisation, and the CITED connection. |

## Install

Claude.ai

1. Download `anti-ai-writing-style-avikbal.skill`.
2. Open Settings, then Capabilities, then Skills.
3. Upload the file. It is ready in any chat.

Claude Code

1. Create a folder `~/.claude/skills/anti-ai-writing-style-avikbal/`.
2. Save the ruleset inside it as `SKILL.md`.
3. Start a session. The skill loads on a matching request.

## Use it

It runs two ways.

Draft mode. Write a piece from scratch in this voice.

Humanize mode. Paste an existing draft and it strips the AI tells out.

Starter prompts:

- "Humanize this draft. Keep the meaning, strip the AI tells: [paste]."
- "Rewrite this so it reads like I wrote it, not a model: [paste]."
- "Write a 600-word post on [topic] in this style. Primary keyword [keyword]."
- "De-AI this email before I send it: [paste]."

## How it works

The skill does two jobs at once. It subtracts the patterns that mark text as machine-made: inflated vocabulary, bloated verbs, dead openings, robotic transitions, reframe sentences, fake depth, and flat rhythm. And it adds what makes writing real: your numbers, your examples, your genuine opinion. When a piece needs a fact it does not have, it asks you for it or marks a placeholder. It never invents one.

That second half is the point. Removing the tells gets you to clean. Adding your real material gets you to yours.

## Why it exists

AI made content cheap and identical. The scarce thing now is writing that sounds like a specific person who knows something. Humanising is not a finishing touch, it is the work, and this skill is the ruleset that does it without faking anything.

## Part of the CITED system

CITED is Avik Bal's framework for how a business gets found, trusted, and chosen when machines answer the questions. CITED fixes where and how you show up. This skill makes the content worth citing, because AI engines quote what is specific, evidence-backed, and clearly written by an expert, not generic model prose. Read the [full guide](anti-ai-writing-style-avikbal-README.md) for the connection.

## Author

Avik Bal is a B2B digital marketing practitioner working in web architecture, SEO, content strategy, and marketing analytics. He is the author of *CITED: The Growth Operating System for AI Search*.

More skills: https://github.com/avikbal-dm

## License

MIT. Copyright 2026 Avik Bal.
