# Portfolio working instructions

Read these files before changing the portfolio:

1. `docs/PROJECT_CONTEXT.md`
2. `docs/WORK_STATUS.md`
3. `docs/DECISION_LOG.md`

Treat those documents and the current repository as the durable source of project context. Use repository-relative paths so the project remains portable.

## Scope and architecture

- This repository is the public portfolio at `https://raghavdharani.github.io/`.
- It is a deliberately simple static site: `index.html`, `styles.css`, `favicon.svg`, and `og.png`.
- GitHub Pages publishes the root of the `main` branch.
- Preserve the static architecture unless a requested capability clearly requires a framework or build system. Document the reason before introducing one.

## Content rules

- Position Raghav as an experienced product leader through evidence, scope, decisions, and outcomes. Do not infer or publish private career motivations.
- Use only claims and metrics already present in the site or explicitly verified by Raghav. Never infer or embellish impact.
- Keep public case studies sanitized. Do not publish client names, confidential employer or customer material, proprietary workflows, or personal information that Raghav has not explicitly approved for public use.
- Employer names already used publicly are acceptable. Customer names are not approved.
- Distinguish shipped professional work from personal experiments and interview exercises. Never present an exercise as a shipped product.
- Write in direct, natural language. Avoid generic portfolio copy, inflated adjectives, stock AI phrasing, emoji-heavy presentation, badge walls, random quotations, vanity statistics, and em dashes.
- Preserve Raghav's preferred public name, email, LinkedIn URL, GitHub URL, and New York location unless he asks to change them.

## Design rules

- Preserve the editorial visual direction: warm paper, deep forest green, burnt orange, pale mint, strong typography, asymmetric spacing, thin rules, and restrained system motifs.
- Current typefaces are DM Sans and Instrument Serif, loaded from Google Fonts with sensible fallbacks.
- Avoid generic portfolio cards, gradients, neon effects, fake application interfaces, device mockups, decorative stock imagery, or gratuitous animation.
- Maintain responsive behavior, semantic HTML, keyboard-accessible links, legible contrast, and reduced-motion support.
- Reuse or deliberately evolve the existing favicon and social preview. Do not ship placeholder imagery.

## Change workflow

- Inspect `git status` before editing and preserve unrelated work.
- Keep `index.html`, metadata, `styles.css`, and durable documentation consistent when positioning or structure changes.
- For content changes, verify every new fact against an approved source or ask Raghav.
- Check the page at desktop and mobile widths when browser testing is requested or available. At minimum, verify anchors, external links, email links, metadata, and the absence of horizontal overflow.
- Check text encoding and ensure intended Unicode characters remain valid UTF-8.
- Update `docs/WORK_STATUS.md` after material work. Add a dated entry to `docs/DECISION_LOG.md` when a durable product, content, design, architecture, privacy, or publishing decision changes.
- Do not commit, push, open a pull request, merge, change GitHub Pages settings, or alter public access unless Raghav explicitly requests it.

## Definition of done

A change is complete when the public-facing copy is accurate and safe, the page remains responsive and accessible, metadata reflects the current site, relevant documentation is current, and requested validation has passed. Report anything that could not be verified.
