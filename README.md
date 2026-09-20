# Ali Bicer — Personal & CMTL² Lab Website

## What's in this folder
- `index.html` — homepage (About)
- `grants.html`, `publications.html`, `presentations.html`, `teaching.html`, `lab.html`, `cv.html` — the other pages
- `cv-data.js` — **all the website's content lives in this one file** (news, publications, presentations, grants, teaching, lab members, CV summary)
- `update.html` — the easy website editor (see below)
- `support.js` — technical file that makes the pages work (never edit)
- `assets/` — photos, member headshots, and the CV PDF

## Publishing on GitHub (one time, ~5 minutes)
1. Create a free account at github.com (or sign in).
2. Click **+ → New repository**. Name it `YOURUSERNAME.github.io` (using your exact username) and make it **Public**. Click **Create repository**.
3. Click **uploading an existing file** (or Add file → Upload files) and drag **everything in this folder** (including the assets folder) into the page. Click **Commit changes**.
4. Wait 1–2 minutes. Your website is live at `https://YOURUSERNAME.github.io`.
5. (Optional) To use a custom domain like alibicer.com: repository **Settings → Pages → Custom domain**, and point the domain's DNS at GitHub Pages per the instructions shown there.

## Updating the website (anytime, ~2 minutes)
1. Open **update.html** — either the live one at `https://YOURUSERNAME.github.io/update.html`, or double-click the file on your computer.
2. Add / edit / delete items in any section (news, publications, presentations, grants, teaching, lab members, CV).
3. Click the yellow **Download updated cv-data.js** button.
4. On your GitHub repository page: **Add file → Upload files** → drag in the downloaded `cv-data.js` → **Commit changes**. Done — the site updates itself.

### Adding a lab member's photo
Upload their picture to the `assets/members` folder on GitHub (Add file → Upload files while inside that folder), then in update.html put its path (e.g. `assets/members/jane.jpg`) in the member's Photo box.

### Replacing the CV PDF
Upload the new PDF to the `assets` folder on GitHub with the exact name `Ali-Bicer-CV.pdf` (it will replace the old one).

### Anything bigger
For changes to the design, the About text, or anything not covered by update.html, paste the relevant file into Claude and describe the change — or ask the person who set this up.
