# 10 Finger Music — Project Context

## What This Is
Marketing/landing page for Eric Rideout's piano teaching and live performance
business (10 Finger Music, St. Louis MO). Single-page static site hosted on
Vercel.

## Services Offered
- Piano lessons (30/45/60 min weekly, pricing published on site)
- Private events (weddings, corporate, celebrations)

## Tech Stack
- Static HTML/CSS/JS — no framework, no build process
- Hosted: Vercel
- Local dev: VS Code + Live Server extension (localhost:5500)

## Deployment
Push to main branch → Vercel auto-deploys within ~1 minute. No
build step required.

## Known Fixes (March 2026)
- Counter animation was stuck at 0 — fixed by populating data-target 
  attributes with correct values (200 events, 30 years experience)

## Outstanding Items
- Portfolio/Music Samples section — empty, needs audio/video content
- Contact form — currently just displays contact info, no form submission
  (recommend Formspree for static-site-compatible form)
- Event pricing — no guidance published, consider adding "starting at" range