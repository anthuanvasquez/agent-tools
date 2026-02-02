# GitHub Copilot — Skills & Prompts

Canonical paths for Copilot-related skills and prompts in this repo:

- `.github/copilot-instructions.md` — top-level Copilot guidance (already present).
- `.github/skills/` — store curated Copilot skills (one folder per skill, containing `SKILL.md`).
- `.github/copilot-sessions/` — short session logs if desired (filename `YYYY-MM-DD-brief.md`).

Skill file example (`.github/skills/unit-test-generator/SKILL.md`):
- Name: unit-test-generator
- Purpose: generate targeted unit tests for a single module using existing patterns
- Prompt: |-
    <prompt text>
- Expected output: a list of tests with test code examples and recommended assertions

Guidance:
- Keep skill prompts minimal and include constraints (time/memory, frameworks). Use `Generated-by: GitHub Copilot` in session logs.
