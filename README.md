# benmingle.com

Personal portfolio site for Ben Mingle, CISSP, CISA — Information Security Compliance Manager.

## What it is

A single-file (`index.html`) static personal site with no build step, no framework, and no dependencies beyond Google Fonts. Sections include:

- **Hero** — intro, subtitle, and contact CTAs (email, LinkedIn)
- **About** — career background (Booz Allen Hamilton, EY, Protiviti, Coalfire, Optiv, Schellman, OBS) and home lab philosophy; stat cards with personal details
- **Life** — hobbies and personal interests (camping, off-roading, fly fishing, skiing, gaming, dog dad)
- **Stack** — home lab hardware and software grouped by Infrastructure, Deployment, and Self-Hosted Services (Proxmox, Coolify, Docker, Unifi, Tailscale, Ollama, Grafana, etc.)
- **Projects** — Home Lab, benmingle.com, Self-Hosted Productivity, Tacoma Build

## Deployment

Self-hosted on [Coolify](https://coolify.io) and exposed via Cloudflare Tunnel. No CI pipeline — Coolify watches the repo and deploys on push.

## Tech

- Pure HTML + CSS (no JavaScript)
- Responsive, mobile-friendly layout
- Hosted on self-owned infrastructure (Proxmox → Coolify → Cloudflare Tunnel → SSL/TLS)
