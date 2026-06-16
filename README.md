# JVS Landscaping — Landing Page

A single-page marketing site for **JVS Landscaping** (Fairport, NY), built from a
Google Stitch export. It's a static site — plain HTML styled with
[Tailwind CSS](https://tailwindcss.com/) (loaded via CDN), Google Fonts, and
Material Symbols. No build step required.

## Run it locally

Just open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

Then visit the URL it prints (usually http://localhost:3000).

## Deploy to Vercel

1. Push this folder to a GitHub repo (see below).
2. Go to https://vercel.com → **Add New… → Project**.
3. **Import** the GitHub repo.
4. Framework preset: **Other** (it's a static site — no build command, output is the root).
5. Click **Deploy**. You'll get a live `*.vercel.app` URL in ~30 seconds.

Every push to the repo's default branch redeploys automatically.

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: JVS Landscaping landing page"
git branch -M main
git remote add origin https://github.com/<your-username>/jvs-landscaping.git
git push -u origin main
```

## Things to customize before going live

- **Phone number** — the "Call John Now" button links to a placeholder
  (`tel:+15850000000`). Replace with the real number in `index.html`.
- **Email** — the "Email Inquiry" button uses `mailto:info@jvslandscaping.com`.
  Replace with the real address.
- **Images** — the photos are AI-generated and currently hosted on Google's CDN
  (`lh3.googleusercontent.com`). These URLs may eventually expire. For a permanent
  site, download the images, drop them in an `images/` folder, and update the
  `src` attributes to point at the local copies.
- **Tailwind CDN** — fine for launch, but it prints a console warning and isn't
  optimized for production. If the site grows, switch to a compiled Tailwind build.

## Files

- `index.html` — the website.
- `vercel.json` — Vercel config (clean URLs).
- `_stitch_export/` — the original, untouched Google Stitch export, including
  `screen.png` (a screenshot of the design) and `DESIGN.md` (the design system).
