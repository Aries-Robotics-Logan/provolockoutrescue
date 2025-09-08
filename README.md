# Provo Lockout Rescue

A simple static website for the car lockout service in Provo, Utah.

## Local preview

Open `index.html` in your browser, or use a small server:

```bash
python -m http.server 5173
```

Then visit http://localhost:5173

## Publish with GitHub Pages (project site)

1. Create a new repository named `provo-lockout-rescue` on your GitHub account.
2. Upload these files (`index.html`, `styles.css`, `script.js`, `README.md`) to the repo root (or push via Git).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
5. Set **Branch** to `main` (or `master`) and **/ (root)` folder. Save.
6. GitHub Pages will publish at `https://<your-username>.github.io/provo-lockout-rescue/` in a minute.

## Alternative: user site

If you prefer `https://<your-username>.github.io`, create a repo named `<your-username>.github.io` and place the files at the root. No Pages settings required.
