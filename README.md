# Product Requirements Skill

Lean PRD skill for Codex. It turns rough feature ideas, stakeholder notes, or requirement drafts into concise product requirements documents that agile teams can align on quickly.

## What It Does

- Creates concise PRDs with a one-page alignment summary.
- Keeps core sections intact: background, user scenarios, flow, core features, acceptance criteria, non-product work, dependencies, risks, and release constraints.
- Uses `Ready / Needs Alignment / Blocked` readiness instead of heavy scoring.
- Marks missing information as `待确认` instead of inventing detail.
- Avoids default over-documentation such as detailed sprint task breakdowns, long DoD lists, and risk matrices unless requested.

## Install

Clone this repository into your Codex skills directory:

```bash
git clone https://github.com/yesaze2077/product-requirements-skill.git ~/.codex/skills/product-requirements
```

Then restart Codex or reload skills.

## Use

Ask Codex for a PRD or product requirements document, for example:

```text
帮我把这个功能想法整理成一个精简 PRD，适合敏捷团队评审。
```

## Public Release Notes

This repository contains only the reusable skill instructions. It does not include private documents, internal URLs, customer data, credentials, or project-specific business metrics.

## License

MIT
