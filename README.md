# Portfolio Site (GitHub Pages Ready)

Simple static portfolio inspired by your reference layout.

## Edit Content

Update these in `index.html`:
- name + bio text
- social links
- project titles, dates, tags, and GitHub URLs
- thumbnail files inside `assets/`

## Run Locally

```bash
cd /Users/christiantheodore/Desktop/codex-projects/portfolio-site
python3 -m http.server 8080
```

Open: `http://localhost:8080`

## Deploy to GitHub Pages

1. Create a repo named `<your-github-username>.github.io` for a root portfolio site.
2. Copy all files from this folder to that repo root.
3. Commit and push to `main`.
4. In GitHub: `Settings -> Pages -> Build and deployment`, set `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Your site will be live at `https://<your-github-username>.github.io/`.

If you already have a different repo name, publish via `gh-pages` branch and access it at:
`https://<your-github-username>.github.io/<repo-name>/`
