# Krunal Desai — Portfolio

A single-page, responsive portfolio site. Plain HTML/CSS/JS — no build step, no dependencies.

## Files
- `index.html` — page structure & content
- `style.css` — all styling (design system in the `:root` tokens at the top)
- `script.js` — mobile nav toggle, animated stats, scroll reveal
- `assets/profile.jpg` — your photo

## Run it locally
Just open `index.html` in a browser, or serve it:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Push it to GitHub
```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/krunal1911/YOUR-REPO-NAME.git
git push -u origin main
```

## Get a live link (pick one)

### Option A — GitHub Pages (free, easiest)
1. Push the repo to GitHub (above).
2. On GitHub: **Settings → Pages → Source → Deploy from branch → main → /(root)**.
3. Your site goes live at `https://krunal1911.github.io/YOUR-REPO-NAME/` in ~1 minute.

### Option B — Vercel
1. Go to vercel.com → **Add New Project** → import your GitHub repo.
2. Framework preset: **Other** (it's static HTML, no build command needed).
3. Deploy. You'll get a `your-project.vercel.app` link, with an option to add a custom domain.

### Option C — Netlify
1. Go to netlify.com → **Add new site → Import an existing project**.
2. Connect the GitHub repo, leave build settings blank (static site).
3. Deploy — you'll get a `your-project.netlify.app` link.

## Things to double check / customize
- **SHEMS** has no GitHub link yet (marked "Repo private — in progress" on the card) — add the repo link in `index.html` once it's public.
- **Webcam Vision Studio** project description was written from the repo name only (not on your resume) — edit it in `index.html` if it doesn't match what the project actually does.
- Phone number is **not shown** on the site (only email + socials) — add it back in the `#contact` section of `index.html` if you'd rather have it public.
- Swap `assets/profile.jpg` for a different image any time — just keep the filename, or update the `src` in `index.html`.
