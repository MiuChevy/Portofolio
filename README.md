# Winson Sovian — Portfolio

A minimal, responsive personal portfolio for **Winson Sovian** — Informatics undergraduate at Universitas Multimedia Nusantara, focused on Quality Assurance, software testing, and security.

🔗 **Live site:** _(add your Vercel URL here after deploy)_

## About

Single-file static website built with plain **HTML, CSS, and JavaScript** — no frameworks, no build step. Loads only Google Fonts (Inter) from a CDN.

### Sections
- **Hero** — intro, call-to-action buttons, and CV download
- **About** — bio, skills & tools, education
- **Projects** — Emora (live app), Emora QA Test Cases, Network Penetration Test, FindMe (UI/UX) — each with an image preview and a detail modal
- **Experience** — organizational and leadership roles
- **Certifications** — courses and bootcamps, each linking to the certificate file
- **Contact** — working contact form (via Formspree) + social links

## Project structure

```
index.html                 → the entire website (HTML + CSS + JS)
winson.jpg                 → profile photo
emora-preview.png          → project image
emora-qa-preview.png       → project image
pentest-preview.png        → project image
findme-poster.jpeg         → project image
CV Winson.pdf              → downloadable CV
*.pdf / *.png              → certificate files linked from the site
```

## Editing

Open `index.html` and look for `<!-- EDIT HERE -->` comments — they mark every spot meant to be customized (text, links, images, the Formspree form ID, etc.).

The contact form uses [Formspree](https://formspree.io). The form endpoint is set in the `<script>` near the bottom of `index.html` (`FORM_ENDPOINT`).

## Deploy (Vercel)

This is a static site, so there is **no build command** and **no output directory** to configure.

1. Push this folder to a GitHub repository.
2. On [vercel.com](https://vercel.com) → **New Project** → **Import** the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**.

After deploying, update the `og:image` and `og:url` meta tags in `index.html` to absolute URLs (e.g. `https://your-domain.vercel.app/winson.jpg`) so social link previews show correctly.

---

© Winson Sovian
