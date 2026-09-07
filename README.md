# MQL → Meeting Performance Dashboard

A static, self-contained interactive dashboard (single `index.html`, no backend/database) visualizing MQL-to-meeting lifecycle performance, in OX Security brand colors.

## Features
- KPI strip (MQLs routed, SDR acceptance rate, meetings held, opportunities created, etc.)
- Lifecycle status map (Marketing qualification → SDR feedback checkpoint)
- Accepted-lead conversion funnel with Count/Rate toggle
- Sub-channel & asset performance tables with Count/Rate toggle
- SDR intake/unqualified/nurture reason breakdowns
- Time range, region, channel, and SDR filters (client-side, illustrative data)

## Run locally
Just open `index.html` in a browser — no build step, no server, no dependencies.

## Deploy
Works as-is on any static host (GitHub Pages, Netlify, Vercel, S3, etc.).

### GitHub Pages
1. Push this repo to GitHub.
2. In the repo settings, enable **Pages** → source: `main` branch, root folder.
3. Your dashboard will be live at `https://<username>.github.io/<repo-name>/`.
