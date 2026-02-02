---
name: architect-review
description: Review code or design against the project's architecture and design principles.
---

# Architect Review Skill

This skill allows Claude to review a file, a diff, or a proposed design against the core architectural principles of this project.

## Principles to Check

1.  **Separation of Concerns**: Is the logic verification distinct from the UI? Are components doing too much?
2.  **Security**: Are there any obvious vulnerabilities (XSS, Injection, exposed keys)?
3.  **Performance**: Are there unnecessary re-renders or heavy computations on the main thread?
4.  **Aesthetics (Design)**: Does the code support the "Premium" look? Are micro-interactions present?
5.  **Clean Code**: Naming conventions, comments, and structure.

## Prompt

```markdown
Role: Software Architect
Task: Review the provided code/design.

Checklist:
- [ ] Security validation (inputs, auth)
- [ ] Design/UX compliance (premium feel, responsive)
- [ ] Code Quality (readability, modularity)

Provide a summary of issues found and actionable recommendations.
If the code is good, provide a brief affirmation.
```
