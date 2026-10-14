# Saad Khan — Portfolio

Personal portfolio site for Saad Khan, Bachelor of Accounting and Financial Management (BAFM) student at the University of Waterloo. It's styled to look like a sheet of green ledger paper.

**Live site:** https://&lt;your-username&gt;.github.io/&lt;repo-name&gt;/

## Files

```
index.html                    Page content
styles.css                    All styling
assets/Saad-Khan-Resume.pdf   Résumé served by the download buttons
```

Plain HTML and CSS: no build step, no dependencies.

## Preview locally

Open `index.html` in a browser, or serve the folder so the résumé download behaves like it does online:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on GitHub Pages (**Settings → Pages → Deploy from a branch → `main` / root**). Every push to `main` updates the live site within a minute or two.

## Updating content

- **Text** (hero, experience, project, skills, contact details) lives in `index.html`.
- **Résumé:** replace `assets/Saad-Khan-Resume.pdf`, keeping the same file name.
- **Layout note:** the page follows a 32px ruled-paper grid (`--line` in `styles.css`). Keep new spacing in multiples of `var(--line)` so text stays on the lines.
