# Decision log

Earlier decisions are retained in the main branch history and project context.

## 2026-10-10: Editorial Astro redesign

**Status:** Proposed in feature branch; pending review and merge.

**Decision**

Rebuild in Astro 5 and Tailwind CSS 4 and deploy statically using GitHub Actions. Use a restrained typographic layout, prominent work narratives, legible evidence and an isolated case study. Remove the contact form in favor of direct email contact.

**Rationale**

User explicitly requested a professional, non-template aesthetic and Astro/Tailwind workflow. The design avoids stock imagery, card repetition, manufactured KPIs, and excessive motion. Existing approved claims remain the public content boundary.

**Publishing dependency**

Switch GitHub Pages Source to GitHub Actions before merging; main currently publishes root static HTML.

**Validation**

Build and browser tests remain required before merging.
