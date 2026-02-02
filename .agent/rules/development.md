---
description: Development standards, technology stack, and implementation workflows.
---

# Development Standards

## Technology Stack

### Core
- **HTML/JS**: Use semantic HTML5 and modern ES6+ JavaScript.
- **CSS**: Vanilla CSS is preferred for maximum control and flexibility.
  - Avoid TailwindCSS unless explicitly requested.
  - If Tailwind is requested, verify version and configuration first.

### Frameworks (If Requested)
- **Web App**: Next.js or Vite.
- **Initialization**: Use `npx -y create-vite-app@latest ./` (or similar) in non-interactive mode.

## Implementation Workflow

1. **Plan**: Understand requirements, research similar implementations, and outline the feature.
2. **Build Foundation**: Set up CSS variables, base styles, and utility functions first.
3. **Components**: Build reusable, self-contained components. Avoid "spaghetti code" by keeping concerns separated.
4. **Assembly**: Integrate components into pages/layouts.
5. **Polish**: Review UX, add micro-interactions, and ensure responsiveness.

## Code Quality

- **Clean Code**: Write self-documenting code with meaningful variable/function names.
- **Comments**: Comment complex logic, but avoid stating the obvious.
- **Formatting**: Adhere to standard Prettier/ESLint configurations.
