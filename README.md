# Matin Farshchi — Personal Landing Page

Static HTML/CSS/JS version for GitHub Pages.

## Run locally

Open `index.html` directly, or use a local server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## Deploy to GitHub Pages

1. Create a repository.
2. Upload:
   - `index.html`
   - `style.css`
   - `script.js`
   - `assets/matin-portrait.jpg`
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/root`.
6. Save.

No build step is required.

## Notes

- Replace `assets/matin-portrait.jpg` with another portrait anytime.
- Update email, LinkedIn and any copy directly in `index.html`.
- The page is responsive and has no external JavaScript dependencies.
