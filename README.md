# Data Forcing Distillation — Supplementary Video Results

Static website showing supplementary qualitative video comparisons for the NeurIPS paper
*Data Forcing Distillation*. Each row compares four methods (Teacher, Ours, DMD2, DP-DMD)
on the same prompt.

## Files

- `index.html` — main page
- `style.css` — styling
- `videos/` — 16 mp4 clips (4 prompts × 4 methods)

## Running locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Hosting on GitHub Pages

1. Create a new public repository on GitHub.
2. Push this folder's contents to the `main` branch:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git add .
   git commit -m "Add supplementary video results website"
   git branch -M main
   git push -u origin main
   ```
3. In the repo's **Settings → Pages**, set source to `Deploy from a branch`, branch
   `main` and folder `/ (root)`, then save.
4. The site will be live at `https://<your-username>.github.io/<repo-name>/`.
