# Raghav Dharani Portfolio

Public portfolio for Raghav Dharani, focused on applied AI, intelligent automation, and verified enterprise product outcomes.

Live site: [raghavdharani.github.io](https://raghavdharani.github.io/)

## Project structure

- `index.html`: public page content and metadata
- `styles.css`: visual system and responsive layout
- `case-study.html`: public-safe KWI product decision record
- `404.html`: custom not-found page
- The contact form posts to FormSubmit, which relays submissions to the portfolio email address after one-time recipient activation.
- `og.png`: social sharing image
- `favicon.svg`: site icon
- `AGENTS.md`: durable working instructions for Codex
- `docs/PROJECT_CONTEXT.md`: goals, audience, positioning, content, and design constraints
- `docs/WORK_STATUS.md`: current state, known limitations, and next steps
- `docs/DECISION_LOG.md`: durable decisions and rationale
- `docs/RELEASE_CHECKLIST.md`: repeatable pre-publish validation

## Local preview

This is a static site with no build step. Serve the repository root with any local HTTP server, then open the local URL it reports. For example:

```bash
python -m http.server 8000
```

## Publishing

GitHub Pages publishes the repository root from `main`. HTTPS is enforced. Material changes should be reviewed locally and merged through a pull request because updates to `main` affect the public site.
