# elinahalonen.com

Personal website for Elina Halonen.

## Deploying to GitHub Pages

1. Push this repo to GitHub
2. Go to Settings → Pages → Source: `main` branch, `/ (root)`
3. GitHub will publish at `https://yourusername.github.io/repo-name`

## Custom Domain

1. In Settings → Pages → Custom domain, enter your domain
2. Add a `CNAME` file to the repo root containing your domain: `elinahalonen.com`
3. Update your DNS: add a CNAME record pointing to `yourusername.github.io`

## Adding Your Photo

1. Save your headshot as `assets/photo.jpg`
2. Commit and push — the site will display it automatically

## Adding the BeS & AI Mapping PDF

1. Save the PDF as `assets/besci-ai-mapping.pdf`
2. Commit and push — the "Download PDF" link will work automatically

## Editing Content

All text content is in `index.html`. Look for comments like:
- `<!-- EDIT: your name -->` — name
- `<!-- EDIT: tagline -->` — intro tagline
- `<!-- EDIT: about text -->` — about paragraph
- `<!-- EDIT: section content -->` — each section
