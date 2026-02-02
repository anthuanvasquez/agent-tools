# Google Antigravity — Rules

This folder follows Google Antigravity documentation conventions.

Structure:
- `.agent/rules/` — repo-level rules for Google Antigravity sessions (format: `YYYY-MM-DD-brief.md`).
- `.agent/workflows/` — recommended workflows and reproducible steps (CI / automation playbooks).
- `.agent/skills/` — curated skill files (prompts, expected outputs, constraints).
- `.agent/sessions/` — session logs and research outputs.

Skill file format (example `.agent/skills/deps-audit.md`):
- Name: dependency-audit
- Purpose: checks dependency health and licensing
- Prompt: |-
    <exact prompt text>
- Expected output: list of top risky deps with citations

Session rules:
- Always include queries used, top sources, and a risk assessment.
- Add `Generated-by: Google Antigravity` header to each session file.
