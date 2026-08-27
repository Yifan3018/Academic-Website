# Personal website — Yi-Fan Lin

Plain HTML/CSS/JS site (no build tools, no framework) with three pages:

- `index.html` — About
- `cv.html` — CV
- `research.html` — Research / projects

## Before publishing, fill in these placeholders

1. **Photo**: add a headshot to `images/headshot.jpg` (index.html already references this path;
   if the file is missing the image area just collapses, so nothing breaks in the meantime).
2. **CV PDF**: copy your CV PDF to `assets/cv/YifanLin_CV.pdf` so the "Download CV" button on
   `cv.html` works.
3. **Links**: `research.html` has several `href="#"` placeholders for paper drafts, code, and
   slides — swap in the real URLs (or a Google Drive / OSF / GitHub link) as they become
   available.

## Preview locally

Just open `index.html` in a browser — no server needed. Or, for a local server:

```
python3 -m http.server 8000
```

then visit http://localhost:8000

## Deploying to GitHub Pages

See the setup steps in the accompanying conversation, or:

1. `git init`, `git add .`, `git commit -m "Initial site"`
2. Create a GitHub repo named `<your-username>.github.io` (for a root user site) or any name
   (for a project site).
3. `git remote add origin <repo-url>`, `git push -u origin main`
4. In the repo's Settings → Pages, set the source branch to `main` (root), or enable it
   automatically if the repo is named `<username>.github.io`.
