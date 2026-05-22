# Astraxis Website Launch Guide

## What is ready

The website is built as a static site in:

`D:\Google Drive Sync\7. M_S\01 AST\Website Build\site`

It includes:

- homepage
- pharma/labs page
- suppliers page
- capabilities page
- quality/trust page
- contact page
- insights archive
- February, March, and April 2026 insight articles
- professional cover images for each insight

## Recommended launch route

Because the domain is on GoDaddy and the user wants low technical burden, use one of these routes:

1. **Fastest no-code route:** rebuild these pages manually in GoDaddy Websites + Marketing using the copy and images from this package.
2. **Cleaner static route:** host this exact static site on Netlify, Cloudflare Pages, Vercel, or GoDaddy cPanel hosting, then connect the GoDaddy domain.

For best control and least builder limitation, use Cloudflare Pages or Netlify. For easiest account/domain handling, use GoDaddy's own website builder.

## Domain steps in GoDaddy

1. Log in to GoDaddy.
2. Open the new domain.
3. Choose the website platform:
   - GoDaddy builder: connect domain inside GoDaddy automatically.
   - Netlify/Cloudflare/Vercel: update DNS records using the host's instructions.
4. Enable HTTPS/SSL.
5. Test both `domain.com` and `www.domain.com`.
6. After the new site is approved, redirect `astraxisintl.com` to the new domain.

## Contact form setup

The static preview uses `mailto:admin@astraxis.com`.

Before going live:

- connect the form to the website platform's form handler
- add WhatsApp click-to-chat only after the public WhatsApp number is approved

## Monthly insights workflow

The monthly automation named `astraxis-monthly-insights-draft` has been created. It prepares a source-backed draft for the most recently completed month and should hold for review if source or image checks fail.

Auto-publishing to the live site still depends on the final hosting platform. Once the platform is chosen, connect the automation to that publishing path.

## Image sources

The current website uses free public images from Pexels, downloaded and cropped into the local site assets folder:

- Cleanroom cart / sterile hallway: Pexels, Tima Miroshnichenko, photo ID 9574476
- Vial handling: Pexels, Ron Lach, photo ID 9893834
- Laboratory computer / controlled lab work: Pexels, Tima Miroshnichenko, photo ID 9574418
- Laboratory touchscreen reference: Pexels, Tima Miroshnichenko, photo ID 9574516

These public images are also used as subpage banner images, with logo-blue overlays applied in CSS for a consistent Astraxis visual system.

Pexels attribution is not required, but retaining source notes is recommended for internal traceability.
