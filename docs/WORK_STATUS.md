# Work status

Last reviewed: 2026-10-10

## Editorial rebuild in review

- Created an Astro 5 + Tailwind CSS 4 static site on a feature branch.
- Rebuilt homepage, shared layout, and Store Transfers decision record.
- Preserved approved, sanitized professional claims from project context.
- Structured work as editorial narratives instead of repetitive portfolio cards.
- Added responsive layouts, skip link, semantic sections and reduced-motion support.
- Moved contact to email, avoiding FormSubmit activation and third-party submission.
- Added GitHub Actions deployment for the Astro `dist/` output.

## Before publishing

- Review the site locally with `npm install && npm run dev`.
- Run `npm run build` and test desktop/mobile, keyboard navigation and link targets.
- Set GitHub Pages Source to GitHub Actions **before merging**.
- Create a new social preview asset for the redesign if desired; the existing remote image is not bundled.
- Confirm whether the direct-contact email should stay publicly visible.

Existing main/root static Pages deployment remains unchanged until merge.
