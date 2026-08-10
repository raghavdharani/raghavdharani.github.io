# Release checklist

Use this checklist before publishing a material portfolio update.

## Content and privacy

- Confirm every new claim and metric against an approved source.
- Confirm that no customer names, confidential artifacts, private records, or unsupported claims are present.
- Label personal work and exercises accurately.
- Keep page metadata consistent with the visible content.

## Navigation and links

- Test every internal navigation link and page-to-page link.
- Test external LinkedIn and GitHub links.
- Test contact-form validation, submission routing, and the successful-submission state.
- Confirm the form recipient has completed the backend's one-time activation.
- Confirm the custom 404 page returns visitors to the site.

## Responsive and accessible behavior

- Review the home page and secondary pages at desktop and mobile widths.
- Check for horizontal overflow and clipped text.
- Navigate all interactive elements using a keyboard.
- Confirm focus visibility, heading order, contrast, and reduced-motion behavior.

## Technical checks

- Confirm intended Unicode characters render correctly as UTF-8.
- Check title, description, canonical URL assumptions, favicon, Open Graph image, and social preview.
- Confirm the site remains usable if Google Fonts do not load.
- Review `git diff` and verify that unrelated local work is preserved.
