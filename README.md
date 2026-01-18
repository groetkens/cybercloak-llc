# cybercloak.llc

This repository hosts the static website for **cybercloak.llc**.

## Purpose

The cybercloak.llc site exists as a credibility and verification endpoint for:
- Executive email communications
- Vendor due diligence
- Compliance and risk review checks

This is **not** a marketing site.
This is **not** a lead generation site.
This is **not** intended for SEO, analytics, or campaigns.

The primary operating and marketing website is:
https://www.cybercloak.tech

## Design Principles

- Mobile-first
- Static HTML and CSS only
- No JavaScript frameworks
- No analytics
- No tracking pixels
- No forms
- No third-party embeds
- Fast load and minimal surface area

The goal is to be boring, clear, and trustworthy.

## File Structure
/
├── index.html
├── styles.css
├── robots.txt
├── sitemap.xml
├── 404.html
├── CNAME
└── .well-known/
└── security.txt

## Hosting

This site is hosted using **GitHub Pages**.

- Source: `main` branch
- Folder: `/ (root)`
- Custom domain: `cybercloak.llc`
- HTTPS enforced via GitHub Pages

DNS configuration:
- Apex domain (`cybercloak.llc`) uses GitHub Pages A records
- `www.cybercloak.llc` is a CNAME to the GitHub Pages hostname

## Making Changes

1. Edit files locally or in GitHub
2. Commit to the `main` branch
3. GitHub Pages automatically rebuilds and deploys

Changes typically go live within a few minutes.

## What Not to Add

Do not add:
- Analytics (Google Analytics, Plausible, etc.)
- Tracking scripts
- Marketing frameworks
- Contact forms
- CMS platforms
- Client-side JavaScript unless strictly necessary

If those needs arise, they belong on **cybercloak.tech**, not here.

## Security Contact

Security issues may be reported to:
security@cybercloak.llc

A security disclosure file is available at:
https://cybercloak.llc/.well-known/security.txt
