# Frontal GTM Skills

A library of Claude Code skills for go-to-market teams: **7 master skills** (each an orchestrator that routes to focused sub-skills) plus **33 standalone skills** covering cold email, Clay, intent signals, list building, LinkedIn ads and content, and n8n.

Part of the [Frontal](https://frontal.so) GTM resource hub.

## Install

Add a whole master skill with one command:

```bash
npx skills add frontal-so/outbound-skills/master-skills/cold-email
```

Swap `cold-email` for any master skill: `clay`, `signal-sourcer`, `list-building`, `linkedin-ads`, `linkedin-content`, `n8n`.

Add a single standalone skill:

```bash
npx skills add frontal-so/outbound-skills/skills/<skill-name>
```

## Master skills

| Skill | Path | Covers |
|---|---|---|
| The Cold Email Strategist | `master-skills/cold-email` | Writing, sequences, deliverability, personalization, infrastructure |
| The Clay Expert | `master-skills/clay` | Tables, waterfalls, credits, Claygent, integrations |
| Intent Signal Analyzer | `master-skills/signal-sourcer` | Buying signals, intent data, scoring, signal to action |
| The List Architect | `master-skills/list-building` | ICP, sourcing, validation, hygiene |
| The LinkedIn Ads Strategist | `master-skills/linkedin-ads` | Setup, targeting, bidding, ABM, creative, measurement |
| The LinkedIn Creator | `master-skills/linkedin-content` | Hooks, storytelling, formats, engagement |
| The n8n Architect | `master-skills/n8n` | Workflow design, triggers, integrations, self-hosting |

Each master skill is an orchestrator: ask it a question and it routes you to the right sub-skill under its folder.

## Standalone skills

33 quick-reference skills live in `skills/`: buying-signal libraries, copywriting frameworks, cold-call scripts, lead-source guides, and more. Browse the folder, or add one directly:

```bash
npx skills add frontal-so/outbound-skills/skills/cold-email-templates-34
```

## Requirements

- [Claude Code](https://code.claude.com/docs) installed
- The `skills` CLI (`npx skills`)

## Credit

Built on the GTM skills library originally developed at ColdIQ. Maintained by [Frontal](https://frontal.so).

## License

MIT, see [LICENSE](LICENSE). Use it, fork it, build on it.
