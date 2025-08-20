# Quarterly Earnings — RevealJS Deck

This repo contains an interactive **RevealJS** presentation suitable for stakeholders. It demonstrates:

- A **Markdown** slide (`data-markdown`)
- **Fragments** for animated reveals
- **Code** samples with syntax highlighting
- **Math** (KaTeX) for financial formulas
- **Speaker notes** (press `S` in presentation to open)
- Your contact: **22ds1000103@ds.study.iitm.ac.in**

## Publish on GitHub Pages

1. Create a new public GitHub repository. Suggested name: **earnings-deck**  
2. Upload these files (or push via Git). The entry file is `index.html` at the repo root.  
3. In the repo: **Settings → Pages → Build and deployment → Branch: `main` (or `master`), Folder: `/root` → Save**.  
4. The site will publish at: `https://<YOUR-USERNAME>.github.io/earnings-deck/`  
5. If updates don't show immediately, refresh with a cache-busting query: `?v=1`, `?v=2`, etc.

Example: `https://octocat.github.io/earnings-deck/?v=3`

## Local preview

You can open `index.html` directly, or serve with a simple HTTP server:

```bash
python -m http.server 8080
# open http://localhost:8080/
```

## Customize

- Change theme by swapping `dist/theme/white.css` for another built-in theme.
- Add slides by inserting more `<section>` blocks or by linking an external Markdown file.
- Replace dummy KPI values with your real quarterly data.
