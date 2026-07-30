# Decision log

This log records durable requirements and implementation choices reflected in the repository and conversation. Each entry identifies whether it was explicitly required or implemented as part of the approved first release.

## 2026-07-29: Use a two-layer portfolio presence

**Status:** Implementation approach accepted when Raghav asked to complete all proposed phases.

**Decision**

Use the special `raghavdharani/raghavdharani` profile repository as a concise front door and the `raghavdharani.github.io` repository as the richer public portfolio.

**Rationale**

A GitHub profile README is effective for quick orientation but cannot provide the layout, responsive presentation, deeper case-study structure, or visual control expected from a portfolio site.

## 2026-07-29: Lead with product outcomes rather than tools or activity

**Status:** First-cut direction accepted when Raghav asked to complete all proposed phases.

**Decision**

Center the portfolio on business problems, Raghav's role, and verified outcomes. Remove badge walls, language statistics, streak widgets, random developer quotes, generator attribution, and excessive emojis from the profile presentation.

**Rationale**

Those elements signal a generic developer template and do not help readers evaluate senior product judgment, scope, or impact.

## 2026-07-29: Use verified, public-safe professional evidence

**Status:** Explicit user requirement to use available source material while keeping private context off the public page; specific published metrics were not independently re-confirmed in this documentation review.

**Decision**

Publish only verified metrics and sanitized descriptions. Exclude client names, confidential employer or customer material, proprietary workflows, unsupported claims, and personal information not explicitly approved for public use.

**Rationale**

The portfolio needs credible evidence without exposing personal data, employer information, customer information, or confidential operating details.

## 2026-07-29: Use an editorial rather than template-driven design

**Status:** First-release implementation choice. The user asked for a professional presentation without standard AI-template signals but did not separately approve this exact palette or typography before implementation.

**Decision**

Use warm paper, deep forest green, burnt orange, pale mint, oversized typography, editorial serif emphasis, strong whitespace, thin rules, and restrained process motifs.

**Rationale**

The desired impression is thoughtful, confident product leadership. Generic portfolio cards, stock imagery, fake product interfaces, and decorative effects would weaken that positioning.

## 2026-07-29: Keep the initial portfolio as a single responsive page

**Status:** First-release implementation choice, not a permanent information-architecture decision.

**Decision**

Launch with one page containing positioning, proof, four selected product examples, operating principles, background, and contact information.

**Rationale**

The first release needed a complete, scannable narrative without waiting for deeper case-study artifacts or introducing unnecessary navigation and maintenance.

## 2026-07-29: Keep the public implementation static

**Status:** First-release implementation choice made to publish the requested portfolio through GitHub Pages. A permanent ban on frameworks was not decided.

**Decision**

Use plain HTML and CSS for the public GitHub Pages repository, with no required JavaScript or build process.

**Rationale**

The current portfolio does not need application state or server features. A static implementation is portable, fast, reliable, easy to host, and easy to move between local folders.

## 2026-07-29: Publish publicly through GitHub Pages

**Status:** Implementation decision required to satisfy the explicit public-facing requirement after managed hosting could not provide anonymous access.

**Decision**

Publish the public site from the root of `main` at `https://raghavdharani.github.io/` with HTTPS enforced.

**Rationale**

The initially prepared managed hosting workspace supported only restricted access. GitHub Pages provided the anonymous public access required for a public-facing portfolio and aligned with the existing GitHub presence.

## Open decisions

The following have not been decided:

- Separate case-study pages versus continued single-page expansion
- Which artifacts can be sanitized and published
- Which professional example should become the first deeper case study
- Whether and how to include personal products or product writing
- Custom domain
- Analytics
- Approval of a public-safe downloadable resume
- Headshot or expanded personal narrative
- Google Fonts hosting approach
- Manual versus automated footer year
- Adoption of the proposed placeholder pages, custom 404 page, and release checklist currently present only as uncommitted local work
