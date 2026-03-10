# Filametric Docs

Official documentation for the Filametric DryBase, built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/).

**Live at:** [docs.filametric.com](https://docs.filametric.com)

## Local Development

### Prerequisites

- Python 3.10+
- pip

### Setup

```bash
# Clone this repo
git clone https://github.com/filametric/docs.git
cd docs

# Install dependencies
pip install mkdocs-material

# Start local dev server
mkdocs serve
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

### Adding Content

1. Edit or create `.md` files in the `docs/` folder.
2. Add images to `docs/images/`.
3. Update `mkdocs.yml` nav section if adding new pages.
4. Commit and push to `main` — GitHub Actions will auto-deploy.

## Deployment

Deployment is automatic via GitHub Actions. Every push to `main` triggers a build and deploys to GitHub Pages.

### Custom Domain Setup

1. In your GitHub repo, go to **Settings → Pages**.
2. Set source to **Deploy from a branch** → `gh-pages`.
3. Add custom domain: `docs.filametric.com`.
4. In your DNS provider, add a CNAME record:
   - Name: `docs`
   - Value: `filametric.github.io`

## Project Structure

```
filametric-docs/
├── .github/
│   └── workflows/
│       └── deploy.yml          # Auto-deploy on push to main
├── docs/
│   ├── images/                 # All images
│   ├── stylesheets/
│   │   └── extra.css           # Filametric brand styling
│   ├── manual/
│   │   ├── introduction.md
│   │   ├── chapter-1-before-you-start.md
│   │   ├── chapter-2-3d-printing.md
│   │   ├── chapter-3-housing-assembly.md
│   │   ├── chapter-4-heating-unit-assembly.md
│   │   ├── chapter-5-drybase-assembly.md
│   │   └── chapter-6-drybox-assembly.md
│   ├── studio/
│   │   ├── overview.md
│   │   └── download.md
│   ├── support/
│   │   ├── faq.md
│   │   └── contact.md
│   └── index.md                # Homepage
└── mkdocs.yml                  # Site configuration
```

## License

Documentation content © 2026 Filametric B.V. All rights reserved.
