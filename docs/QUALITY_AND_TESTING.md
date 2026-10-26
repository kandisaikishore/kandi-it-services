# Static Website Development and QA Guide

This website uses HTML, CSS, JavaScript, and supporting visual assets. The current repository source defines the page content and interactions; do not assume a backend or contact-form delivery service exists unless implemented.

## Run locally

```bash
git clone https://github.com/kandisaikishore/kandi-it-services.git
cd kandi-it-services
```

Open `index.html` in a modern browser or use a simple local static server for consistent asset paths.

## Quality checks

- Verify internal links and local image, CSS, and JavaScript references resolve.
- Check page title, language declaration, heading hierarchy, and metadata.
- Ensure interactive controls have accessible names and visible keyboard focus.
- Provide meaningful alt text for informative images.
- Test mobile, tablet, and desktop layouts and zoom behavior.
- Check for browser console errors and failed network requests.

## Contact journey

If a contact form is implemented, validate required fields, malformed addresses, repeated submissions, and server failure. Show success only after the submission is actually confirmed. If contact is handled only by an email or telephone link, verify the link target but do not claim a message was delivered.

## Deployment status

A GitHub repository URL is not a live deployment. Only add a public deployment link after checking the live site and confirming its behavior.

## Pull-request checklist

- [ ] Test changed content and links in a browser.
- [ ] Verify local assets, keyboard access, and responsive layout.
- [ ] Preserve existing brand content unless a defect requires a change.
- [ ] State which checks were manual or unavailable.
