# Medplix.AI — Landing Page

A fast, SEO-friendly, lead-generating landing page for **Medplix.AI** — the AI-powered
healthcare management platform for hospitals, clinics, labs and pharmacies.

Pure HTML/CSS/JS — no build step. Just open `index.html` or host the folder anywhere.

## Files
| File | Purpose |
|------|---------|
| `index.html` | All page content + SEO meta + JSON-LD structured data |
| `styles.css` | All styling, fully responsive |
| `script.js` | Mobile nav, mega-menu, AJAX lead form |
| `assets/logo.svg` | Logo (swap with your PNG if you prefer — see below) |
| `robots.txt`, `sitemap.xml`, `site.webmanifest` | SEO / PWA support |

## ✅ Go-live checklist (do these to make it production-ready)

1. **Connect the lead form (most important).**
   - Sign up free at <https://web3forms.com> with your email — leads land in your inbox.
   - Copy your **Access Key**.
   - In `index.html`, find `YOUR_WEB3FORMS_ACCESS_KEY` and replace it with your key.
   - Done — every demo request is now emailed to you. (Until then the form shows a
     friendly "Thank you" without sending, so it's never broken.)
   - *Alternative:* Formspree, Google Forms, or your own CRM endpoint — just change
     the `<form action="…">` and the hidden `access_key`.

2. **Set your real domain.** Replace every `https://medplix.ai/` in `index.html`,
   `sitemap.xml` and `robots.txt` with your actual domain (canonical URL, Open Graph,
   structured data, sitemap).

3. **Add a social share image** at `assets/og-image.png` (1200×630px) — used when the
   link is shared on WhatsApp / LinkedIn / Facebook.

4. **(Optional) Use your exact logo.** Drop your PNG as `assets/logo.png`, then in
   `index.html` change the three `assets/logo.svg` references to `assets/logo.png`.

5. **Verify contact details.** Phone `95408 89999` / `+91 95408 89999` and
   `support@medplix.ai` appear in the header, footer, WhatsApp button and structured
   data — update if needed.

6. **Submit to Google.** Add the site to [Google Search Console](https://search.google.com/search-console)
   and submit `sitemap.xml` for indexing. Optionally add Google Analytics / GA4.

## SEO included
- Semantic HTML5, single `<h1>`, clean heading hierarchy
- Meta description + keywords, canonical URL, theme color
- Open Graph + Twitter Card tags
- JSON-LD: Organization, WebSite, SoftwareApplication (with pricing), FAQPage
- `robots.txt` + `sitemap.xml` + web manifest
- Fast (no frameworks), mobile-first responsive, accessible (skip link, focus states, reduced-motion)

## Deploy
Upload the whole folder to any static host — **Netlify, Vercel, Cloudflare Pages,
GitHub Pages, Hostinger, cPanel**. No server needed.
