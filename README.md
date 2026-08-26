# Sebastian Liste — Netlify Deployment

Static site (flat .html files, no build step). `netlify.toml` is already
set up with `publish = "."` and no build command.

## Deploy

**Drag-and-drop (fastest):**
Drag this whole folder onto https://app.netlify.com/drop.

**Netlify CLI:**
```
cd netlify
netlify deploy --prod
```

**Git-based deploy:**
Push this folder to a repo and connect it in the Netlify dashboard.
Build settings are already defined in `netlify.toml`
(`publish = "."`, no build command needed).

The site will resolve at `https://sebastianliste.netlify.app/` by default,
which matches the canonical URLs, Open Graph tags, structured data, and
sitemap.xml already in this folder. If you attach a custom domain instead,
update those references to match.

## What's in this folder

```
├── index.html
├── about.html
├── contact.html
├── privacy.html
├── amazon-decade-long-project.html
├── what-photodocumentarians-is.html
├── photodocumentarians-opens-global-community.html
├── netlify.toml
├── sitemap.xml
├── robots.txt
├── assets/style.css
└── images/
```
