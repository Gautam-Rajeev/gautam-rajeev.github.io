# Personal site (GitHub Pages)

Static portfolio for **Gautam Rajeev** — built for hosting on [GitHub Pages](https://pages.github.com/).

## Local preview

Open `index.html` in a browser, or from this folder run a quick static server, for example:

```bash
npx --yes serve .
```

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. In the repo on GitHub: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** (or `master`) and folder **`/ (root)`**, then save.

### User site vs project site

- **User site** (URL `https://YOUR_USERNAME.github.io/`): use a repository named **`YOUR_USERNAME.github.io`** and put these files in its root.
- **Project site** (URL `https://YOUR_USERNAME.github.io/REPO_NAME/`): enable Pages on this repo; relative links in this project already work for that layout.

## Customize

- **GitHub profile URL**: search for `github.com/gautamrajee` in `index.html` and replace with your username if different.
- **Resume file**: the Download button points to `Gautam resume (7).pdf` in the repo root. Rename the file or move it and update the `href` in `index.html` accordingly.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page structure and content |
| `styles.css` | Layout and theme |
| `script.js` | Mobile nav + footer year |
| `.nojekyll` | Ensures Pages serves all paths as static files |
| `Gautam resume (7).pdf` | Resume download |
