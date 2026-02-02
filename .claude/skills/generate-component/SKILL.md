---
name: generate-component
description: Generate a UI component following the premium design system.
---

# Generate Component Skill

This skill guides Claude to generate a new UI component (HTML/CSS/JS or Framework) that adheres to the "Premium" design guidelines.

## Instructions for Claude

1.  **Input**: Receive the description of the component (e.g., "A login card", "A data dashboard widget").
2.  **Style Guide Application**:
    - Use Vibrant Colors (HSL).
    - Use Modern Typography (Inter/Roboto).
    - Apply Micro-animations (hover scales, fades).
    - Ensure Accessibility (A11y).
3.  **Output Format**:
    - Provide the code (HTML/CSS/JS).
    - Provide a brief explanation of the design choices.

## Prompt Template

```markdown
Create a [Component Name] that matches our Premium Design terminology.
- It should look modern, sleek, and high-quality.
- Include hover effects and smooth transitions.
- Use a color palette of [Color Preference, e.g., Deep Blue and Neon Cyan].
- Output the full code.
```
