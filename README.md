# NyumbaTrack Website

Marketing landing page for **NyumbaTrack** — property management software for Kenyan landlords and agents.

This is a single static `index.html` file (no build step required).

## Stack
- HTML + CSS (no framework)
- Google Fonts: Plus Jakarta Sans (display) + Inter (body)
- Inline SVG icons

## Sections
- Hero with app phone mockup
- Features grid
- How it works (3 steps)
- Roles: Landlord vs Agent
- Pricing (5% of rent collected, annual discount)
- Call to action (WhatsApp + email)
- Footer

## Deploy
Deploy directly to Vercel:
1. Push this repo to GitHub
2. Import the repo in Vercel
3. No build command needed — it's a static site

## Editing
All content lives in `index.html`. Update:
- WhatsApp number / email in the CTA buttons
- Copy in each `<section>`
- Colors via CSS variables at the top of the `<style>` block (`:root`)

## App
The actual NyumbaTrack app lives in a separate repo: `nyumbatrack` — deployed at [nyumbatrack.vercel.app](https://nyumbatrack.vercel.app)

---
© 2026 NyumbaTrack Technologies Ltd. Built for Kenyan landlords.
