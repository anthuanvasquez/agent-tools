---
description: Workflow to scaffold a new web project with the preferred technology stack.
---

# Scaffold New Project

This workflow sets up a new web project using the standard stack (Vite/Next.js) with the configuration defined in the rules.

## Steps

1. **Verify Requirements**
   - Check if `node` and `npm` are installed.
   - Confirm the target directory is empty or safe to write to.

2. **Initialize Project**
   - Run the creation command:
     ```bash
     npx -y create-vite@latest . --template vanilla
     ```
     *(Adjust template based on specific user request, e.g., react, vue)*

3. **Install Dependencies**
   - Run `npm install`.

4. **Setup Base Styles**
   - Replace `style.css` with the project's design system variables (colors, typography).
   - Ensure `index.html` has proper meta tags for SEO.

5. **Initial Commit**
   - Initialize git repo: `git init`
   - Create `.gitignore`
   - Stage and commit initial files.

// turbo
6. **Report Status**
   - Output the success message and instructions to start the dev server (`npm run dev`).
