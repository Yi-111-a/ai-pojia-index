# Search Method

Snapshot date: 2026-08-03, Asia/Shanghai.

This index was built from public GitHub search results and repository metadata. Star counts are point-in-time values and may drift.

## Primary Search Queries

Strong Codex / GPT-5.6 / pojia cluster:

```powershell
gh search repos 'gpt-5.6-instruct' --sort stars --order desc --limit 100
gh search repos 'Codex jailbreak' --sort stars --order desc --limit 100
gh search repos 'Codex 破甲' --sort stars --order desc --limit 100
gh search repos '5.6 JAILBREAK NERV codex instruct' --sort stars --order desc --limit 100
gh search repos 'GPT-5.5 Codex Claude Cursor' --sort stars --order desc --limit 100
gh search repos '破限 codex' --sort stars --order desc --limit 100
```

General LLM jailbreak / red-team cluster:

```powershell
gh search repos 'LLM jailbreak' --sort stars --order desc --limit 100
gh search repos 'jailbreak prompts ChatGPT' --sort stars --order desc --limit 100
gh search repos 'LLM red team' --sort stars --order desc --limit 100
gh search repos 'AI jailbreak prompts' --sort stars --order desc --limit 100
```

Prompt injection and defense cluster:

```powershell
gh search repos 'prompt injection' --sort stars --order desc --limit 100
gh search repos 'prompt injection llm security' --sort stars --order desc --limit 100
gh search repos 'awesome prompt injection' --sort stars --order desc --limit 100
gh search repos 'codex prompt injection' --sort stars --order desc --limit 100
gh search repos 'codex system prompt' --sort stars --order desc --limit 100
```

## Metadata Fields

The index uses:

```powershell
--json fullName,url,description,isFork,isArchived,stargazersCount,updatedAt,language
```

## Classification Rules

- `codex-gpt56-pojia`: strong match for Codex, GPT-5.6, Claude Code, Cursor, jailbreak, pojia, or polimit.
- `codex-agent-tools`: local patch, system prompt, skill, MCP, or agent tooling adjacent to Codex / coding agents.
- `llm-jailbreak-redteam`: general LLM jailbreak, red-team benchmark, prompt generator, or adversarial testing repo.
- `prompt-injection-defense`: prompt injection, detection, guardrail, scanner, firewall, MCP security, or defensive tooling.
- `resource-list`: curated lists, handbooks, roadmaps, field manuals, or paper lists.

## Safety Boundary

This repository keeps a link-only index. It intentionally avoids copying:

- Operational jailbreak prompts
- Bypass recipes
- Payload bodies
- Full exploit walkthroughs
- Secret extraction strings or prompt leak text

Short neutral notes are used instead of reproducing repository instructions.

## Refresh Checklist

1. Re-run the queries above.
2. Export JSON metadata from GitHub CLI.
3. Merge results and de-duplicate by `fullName`.
4. Assign categories using the rules above.
5. Sort by `stargazersCount` descending inside each category.
6. Update `README.md`, `data/repos.csv`, and `data/repos.json`.

