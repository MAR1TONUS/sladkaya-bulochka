
# Skazochki — Deploy Instructions

This folder contains a single-page app:
- `index.html` — main file (welcome flow, terms, content, countdown).

## Deploy to GitHub Pages (no build)
1) Create a new repo on GitHub (public): `skazochki-site`.
2) Upload `index.html` (drag & drop to the repo → Commit).
3) Open **Settings → Pages**.
4) Under **Build and deployment**, choose **Source: Deploy from a branch**.
5) Branch: `main` (or `master`), Folder: `/ (root)`. Save.
6) Wait ~1 min. The site appears at: `https://<your-username>.github.io/skazochki-site/`.

## Deploy to Netlify (drag & drop)
1) Go to https://app.netlify.com/drop
2) Drag the `index.html` file.
3) After upload, you'll get a public URL like `https://something.netlify.app/`.
4) You can change the site name in Site settings → Domain management.

## Reset welcome state
Append `#reset` to the URL to clear localStorage and re-show the welcome modal:  
`https://.../index.html#reset`
