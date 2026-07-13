# Wealth Forge Co — Website

Full-service Meta Advertising & Website Design agency website.

## Deployment — Cloudflare Pages via GitHub

1. Push this entire folder to a GitHub repository
2. Go to [Cloudflare Pages](https://pages.cloudflare.com)
3. Connect your GitHub account → select the repository
4. Build settings:
   - **Framework preset**: None (Static HTML)
   - **Build command**: *(leave blank)*
   - **Build output directory**: `/` (root)
5. Click **Save and Deploy**

## Project Structure

```
wealthforgeco/
├── index.html              ← Main homepage
├── privacy-policy.html     ← Privacy Policy
├── terms.html              ← Terms of Service
├── robots.txt              ← Search engine crawl rules
├── sitemap.xml             ← Sitemap for SEO
├── _redirects              ← Cloudflare Pages URL redirects
├── _headers                ← Cloudflare Pages security headers
└── assets/
    ├── css/
    │   ├── main.css        ← All homepage styles
    │   └── legal.css       ← Privacy & Terms styles
    ├── js/
    │   └── main.js         ← All JavaScript (phone mask, hamburger, translate, waitlist form)
    ├── fonts/              ← (Reserved for self-hosted fonts if needed)
    └── images/
        ├── favicon.ico
        ├── favicon-16x16.png
        ├── favicon-32x32.png
        ├── favicon-180x180.png
        ├── favicon-192x192.png
        └── favicon-512x512.png
```

## Before Going Live

1. **Formspree** — Log into formspree.io with wealthforgeco@outlook.com and confirm
   the email so waitlist form submissions are delivered to your inbox.
2. **Domain** — Point your domain (e.g. wealthforgeco.com) to Cloudflare Pages
   in the Pages dashboard under Custom Domains.
3. **Update sitemap** — Replace `https://wealthforgeco.com` with your actual domain.
4. **Update robots.txt** — Replace the sitemap URL with your actual domain.

## Services Used

- **Formspree** (mqevpygr) — Waitlist form submissions → wealthforgeco@outlook.com
- **Google Fonts** (CDN) — Playfair Display, Inter, Space Mono
- **Google Translate** — In-page language switcher (35 languages)
- **Sitedrop.ai** — Client website creation service

## Social Links

- Facebook: https://www.facebook.com/profile.php?id=61586273708307
- Instagram: https://www.instagram.com/wealthforgeco
