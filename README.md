# Rukh by Mah — Vercel-ready static website

A zero-build, multi-page static website for Rukh by Mah. It is designed to deploy directly to Vercel with no Node.js/npm dependency.

## Included
- Responsive premium editorial homepage
- Collections, Journal, Upcoming, Why Rukh, Reviews, Location and Customer Care pages
- Local WebP image library in `assets/images/`
- Responsive navigation and mobile menu
- Touch/arrow/auto sliders
- Scroll-reveal animations with reduced-motion support
- WhatsApp and Instagram links
- Google Maps location embed
- Custom 404 page
- `robots.txt` and `sitemap.xml`
- Vercel configuration with clean URLs, security headers and long-term asset caching
- SVG favicon

## Deploy to Vercel
1. Extract this ZIP.
2. Upload the **contents** of this folder to the root of a GitHub repository.
3. Import the repository into Vercel.
4. Framework Preset: **Other**
5. Root Directory: **./**
6. Build Command: **leave empty**
7. Install Command: **leave empty**
8. Output Directory: **leave empty**
9. Deploy.

There is no build step. Vercel serves the HTML, images and other static assets directly.

## Clean URLs
Vercel is configured with `cleanUrls: true`, so these pages can be visited as:
- `/`
- `/collection`
- `/articles`
- `/upcoming`
- `/why-us`
- `/reviews`
- `/location`
- `/customer-care`

The original `.html` files are still included for static hosting compatibility.

## Business details currently in the site
- Store: F-11 Markaz, Mall of Islamabad, Islamabad
- WhatsApp: +92 313 9392003
- Instagram: @rukhbymah

Before launch, replace any demo/placeholder customer reviews with verified reviews and confirm the business contact/location details.

## Local testing
Because this is a static site, it can also be tested locally with any static HTTP server. Opening `index.html` directly from the filesystem may work, but an HTTP server is recommended.
