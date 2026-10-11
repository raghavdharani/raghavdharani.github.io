# Raghav Dharani — Portfolio

Personal portfolio built with Astro 5 and Tailwind CSS 4. The site is static and hosted on GitHub Pages.

## Run locally

Requires Node.js 22+.

```bash
npm install
npm run dev
```

Open http://localhost:4321.

## Build and preview

```bash
npm run build
npm run preview
```

The deployable static site is generated in `dist/`.

## Publishing

Merge the editorial redesign pull request after review. The GitHub Actions workflow deploys `dist/` to GitHub Pages. **Before merging**, change repository Settings → Pages → Build and deployment → Source to **GitHub Actions**. Otherwise the existing main-branch/root Pages publishing mode will not serve the Astro output.

## Content and implementation

- `src/pages/index.astro`: homepage and selected work
- `src/pages/case-study/index.astro`: Store Transfers decision record
- `src/layouts/Base.astro`: shared metadata and navigation
- `src/styles/global.css`: design tokens, responsive typography and layout
- `public/`: static assets
- `docs/`: editorial constraints, evidence rules and decision history

No resume PDF is distributed. Public copy uses previously approved claims from repository documentation. No client names or confidential materials are included. Contact uses an email link rather than a third-party form backend.

## Design discipline

This is an editorial system influenced by Impeccable principles: deliberate hierarchy, consistent spacing and type scales, contrast, restrained animation, responsive and accessible markup, and the removal of generic cards, badges and decorative UI. It is not a claim that an Impeccable CLI or audit was executed.
