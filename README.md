# Webdesign Studio — Showcase

A single-file static website showcasing eight distinct web-design styles, each
reachable from the left side menu. Every style restyles the whole interface
(typography, colours, layout and the menu itself):

Home · Dark · Light · Modern · Old School (Windows 95) · Business · Sport · NGO

The site is fully self-contained — all visuals work out of the box via CSS
gradients and inline SVG art. Two spots can optionally use real photography;
see [`images/README.txt`](images/README.txt).

## View locally

Just open `index.html` in any browser (double-click). No build step, no server.

## Deploy for free

**Netlify Drop (easiest, no account needed to try):**
1. Go to https://app.netlify.com/drop
2. Drag this whole folder (`index.html` **and** `images/`) onto the page
3. You get a live URL instantly (e.g. `your-name.netlify.app`)

**GitHub Pages (this repo is already git-initialised):**
1. Create an empty repo on GitHub
2. `git remote add origin https://github.com/<you>/<repo>.git`
3. `git push -u origin main`
4. In the repo: Settings → Pages → Source = `main` / root → Save
5. Your site goes live at `https://<you>.github.io/<repo>/`

Other free static hosts that also work: Cloudflare Pages, Vercel, GitLab Pages.
