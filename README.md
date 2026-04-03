# EmDash Docs Template

A clean, professional documentation template for [EmDash CMS](https://emdashcms.com). Perfect for documenting products, APIs, libraries, and open-source projects.

## Features

- Hierarchical sidebar navigation with section grouping
- Table of contents with scroll spy
- Full-text search
- Dark mode with system preference detection
- Code blocks with syntax highlighting
- Callout/admonition blocks (info, warning, tip, danger)
- Responsive design — mobile-friendly sidebar
- SEO-optimized with meta tags and canonical URLs
- Breadcrumb navigation
- Previous/Next document navigation

## Deploy

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/awebsomestuff/emdash-template-docs)

## Local Development

```bash
npm install
npx emdash dev
```

Visit `http://localhost:4321` for the site and `http://localhost:4321/_emdash/admin` for the admin panel.

## Built With

- [Astro](https://astro.build) — Web framework
- [EmDash CMS](https://emdashcms.com) — Content management
- [Cloudflare](https://cloudflare.com) — D1 database + R2 storage + Workers
