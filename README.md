# Bamboo Buds Academy — Site 

This repository contains a simple static homepage for Bamboo Buds Academy (Pre-K).

## Local preview

Open `index.html` in your browser locally. For a simple static server (recommended):

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy options

### GitHub Pages
1. Commit the files to a GitHub repository.
2. In repository Settings → Pages, select the `main` branch and root `/` folder.
3. Save — the site will be available at `https://<your-user>.github.io/<repo>/`.

### Netlify
1. Create a Netlify account and connect your GitHub repo.
2. For a simple static site, no build command is necessary — set the publish directory to `/`.
3. Trigger a deploy; Netlify will provide a domain or allow you to add a custom domain.

### Vercel
1. Connect the GitHub repo to Vercel and import the project.
2. Use default settings (static site). Vercel will deploy and provide a preview and production URL.

## Next steps (suggested)
- Add real images and copy.
- Add a contact form or integration (Formspree, Netlify Forms).
- Add analytics and accessibility checks.
