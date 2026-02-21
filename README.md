# asifmahmud.github.io
Asif Mahmud Portfolio — a simple, responsive portfolio site ready to deploy on GitHub Pages.

## Deploy to GitHub Pages

### Option A: New repo for portfolio only

1. **Create a new repository** on GitHub (e.g. `username.github.io` for your personal site, or `portfolio`).

2. **Push the portfolio files** as the root of that repo:
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** in the repo:
   - Go to **Settings → Pages**
   - Under "Source", choose **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
   - Save

4. After a few minutes, your site will be live at:
   - `https://YOUR_USERNAME.github.io/YOUR_REPO/` (if repo is `portfolio`)
   - `https://YOUR_USERNAME.github.io/` (if repo is `username.github.io`)

### Option B: Portfolio in this repo

GitHub Pages only supports root or `/docs`. To use this repo:

1. **Using root:** Move `index.html` and `styles.css` from `portfolio/` to the repo root.
2. Push to GitHub.
3. In repo **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**.

## Customize

- Replace `[Your Name]` in `index.html`
- Update project cards with real projects and links
- Update contact links (email, GitHub, LinkedIn)
