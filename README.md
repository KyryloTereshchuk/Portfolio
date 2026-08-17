# Kyrylo Tereshchuk — Product Designer Portfolio

Responsive one-page portfolio in Ukrainian and English. Built with plain HTML, CSS, and JavaScript, so it can be opened locally or deployed to any static host.

## Page structure

1. **Hero** — positioning, experience, focus, location, and primary CTA.
2. **Selected work** — Qela, an NDA-protected project, and Zelvo case previews.
3. **Process** — four stages from context to implementation.
4. **Contact** — availability statement and email CTA.

## Run locally

Open `index.html` directly or start the Vite development server:

```bash
npm install
npm run dev
```

The terminal will show the local preview URL. A simple `python3 -m http.server 4173` also works.

## Before publishing

- Confirm the contact email in `script.js` before publishing.
- Review what can be disclosed publicly for each case, especially Zelvo.
- Replace the case preview dialogs with full case-study pages when materials are ready.
- Add analytics only after choosing a privacy-compliant setup.

## Content notes

- No product metrics were invented.
- The Qela and NDA-protected project descriptions use known product scope.
- The Zelvo description is intentionally broad because the public NDA scope is not defined.
