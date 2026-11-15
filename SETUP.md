# Maths Notes & Flashcards Setup Guide

## Live URLs
- **Notes Index:** `https://github.io`
- **Flashcards:** `https://github.iocards/`

## Daily Update Workflow (Fedora Terminal)
1. Edit `index.html` or `cards/index.html` locally.
2. Double-click the `.html` file to preview equations in Brave.
3. Push updates to GitHub Pages:
   ```bash
   git add .
   git commit -m "Update maths notes"
   git push
   ```
4. Wait ~60 seconds, then press `Ctrl + Shift + R` in Brave to hard-refresh the live site.

## Key Reminders
- **MathJax CDN:** `https://cloudflare.com`
- **LaTeX Delimiters:** Use `\(...\)` for inline math and `\[...\]` or `$$...$$` for display math.
- **Git Auth:** Token is saved in `~/.git-credentials`. When it expires, generate a new Classic Token with the `repo` scope on GitHub and paste it at the `Password:` prompt.

