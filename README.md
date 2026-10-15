# New Muslim Compass — website layout

Static HTML/CSS mockup of the New Muslim Compass site (design only — the forms don't submit anywhere yet). Open `index.html` in a browser to preview, or click through the pages from the nav bar.

Pages: `index.html` (Home), `need-help.html`, `groups.html`, `find-a-masjid.html`, `get-involved.html`, `events.html`, `free-resources.html`, `learn.html`.

Anywhere real content is missing (phone number, address, chapter names, testimonial, event details) is marked with a bracketed placeholder like `[phone number]` — replace those before this goes live.

## Push to GitHub

If you don't already have Git installed, grab it from https://git-scm.com/downloads first. Then, from inside this folder:

```bash
git init
git add .
git commit -m "Initial website layout"
```

Create the empty repo on GitHub first (https://github.com/new → name it `new-muslim-compass`, set it to **Private**, don't add a README/gitignore there), then:

```bash
git branch -M main
git remote add origin https://github.com/<your-username>/new-muslim-compass.git
git push -u origin main
```

Replace `<your-username>` with your actual GitHub username. If you'd rather use GitHub Desktop or VS Code's built-in Git UI instead of the command line, you can just point either of those at this folder and publish it from there — same result.

## Hosting it for free (optional)

Once it's on GitHub, you can turn on **GitHub Pages** (repo → Settings → Pages → Deploy from branch → `main` / root) to get a live URL for the site — note Pages only serves *public* repos on a free plan, so you'd need to flip visibility to Public first if you want that.
