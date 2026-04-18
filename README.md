# benmingle.com

Personal portfolio site for Ben Mingle, CISSP, CISA — Senior GRC & Information Security Consultant.

## What it is

A single-file (`index.html`) static personal site with no build step, no framework, and no dependencies beyond Google Fonts. Sections include:

- **Hero** — intro, certifications, and contact CTAs
- **About** — career background (Booz Allen Hamilton, EY, Protiviti, Coalfire, Optiv, Schellman, OBS) and home lab philosophy
- **Stack** — home lab hardware and software (Proxmox, Coolify, Docker, Unifi, Tailscale, Grafana, etc.)
- **Projects** — home lab dashboard, automation bot, self-hosted stack configs, and this site itself

## Deployment

Self-hosted on [Coolify](https://coolify.io) via a git push. No CI pipeline — Coolify watches the repo and deploys on push.

## Tech

- Pure HTML + CSS (no JavaScript)
- Responsive, mobile-friendly layout
- Hosted on self-owned infrastructure (Proxmox → Coolify → reverse proxy → SSL/TLS)
