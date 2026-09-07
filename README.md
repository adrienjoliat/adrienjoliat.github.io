# Adrien Joliat — Portfolio

Personal portfolio of Adrien Joliat, built with Astro and deployed as a static website with GitHub Pages.

## Local development

Requirements:

- Node.js 22.12 or newer (use an even-numbered supported release)
- npm

```bash
npm install
npm run dev
```

Astro will print the local development URL in the terminal.

## Production build

```bash
npm run build
npm run preview
```

## Deployment

The site is configured for the special GitHub Pages repository:

`adrienjoliat/adrienjoliat.github.io`

Every push to `main` triggers `.github/workflows/deploy.yml` and publishes the built Astro site through GitHub Pages.

In GitHub repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.

## Design direction

The portfolio will use a dark scientific/space visual identity and an information architecture influenced by Brittany Chiang's v4 portfolio while being rebuilt as a modern Astro implementation.

Reference: https://github.com/bchiang7/v4

## Third-party notice

Brittany Chiang's `bchiang7/v4` repository is MIT licensed. If portions of its source code are incorporated later, its copyright and MIT license notice must be preserved in accordance with that license.
