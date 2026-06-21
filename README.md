# SEO Audit Pro — Landing Page

**Live:** https://unknown-user-status.github.io/seo-audit-landing/
**Backend:** https://seo-audit-pro-i834.onrender.com
**Main repo:** https://github.com/unknown-user-status/seo-audit

---

## What This Is

Public landing/marketing page for SEO Audit Pro — an AI-powered SEO audit SaaS. Hosted on GitHub Pages.

## Features

- Hero section with value proposition
- 6 feature cards (AI analysis, PDF reports, 12 categories, etc.)
- "How It Works" 3-step guide
- Pricing table: Free ($0), One-Time ($49), Pro ($99/mo), Agency ($199/mo)
- Stripe.js checkout integration (test mode)
- Email collection before checkout
- Nav bar with Dashboard link
- FAQ section

## How It Works

1. User enters URL + email on landing page
2. Redirected to Stripe Checkout (or free signup)
3. Backend processes payment via webhook
4. Crawls site, analyzes SEO, generates AI report, builds PDF
5. Emails PDF to user

## Tech

- Static HTML + inline CSS (dark navy `#1a1a2e` + red `#e94560` theme)
- Stripe.js for checkout buttons
- Points to Render backend for API calls

## Deploy

Push to `main` branch → GitHub Pages auto-deploys from repo root.
