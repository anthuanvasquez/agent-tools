# Claude Code

Canonical paths for Claude usage in this repository:

- `.claude/rules/` — rules for Claude Code
- `.claude/skills/` — reusable skills (one folder per skill, containing `SKILL.md`)
- `.claude/CLAUDE.md` — Claude Code instructions
- `.claude/settings.json` — Claude Code settings


Skill file example (`.claude/skills/spec-draft.md`):
- Name: spec-draft
- Purpose: Draft an initial feature spec using the provided acceptance criteria
- Prompt: |-
    <full prompt text>
- Expected outputs: `docs/specs/<feature>.md` draft + short tradeoff summary

Session guidelines:
- Add `Generated-by: Claude` header; include model and version if available; add links to drafts in `docs/specs/`.
