# PL Dev Guild · Cohort 6 Engagement Dashboard

A live engagement analytics dashboard for the [Protocol Labs Developer Guild](https://pldg.xyz) Cohort 6 program (January – March 2026).

**Live dashboard:** [anubha-mane.github.io/pldg-cohort6-dashboard](https://anubha-mane.github.io/pldg-cohort6-dashboard/)

---

## What it shows

- **Weekly submissions and active contributors** across all 11 program weeks
- **Tech partner engagement** — Libp2p, Storacha, Akave, Fil-Oz, Drand, OSO and more
- **NPS and sentiment trends** — weekly scores, promoter/passive/detractor breakdown, mentor ratings
- **Contributor leaderboard** — sorted by total weeks submitted with per-week activity grid
- **Submission checker** — contributors can look up their own record by email or GitHub username

## Data

- **617 weekly engagement survey (WES) submissions** across 79 contributors
- **11 program weeks** — Jan 11 through Mar 27, 2026
- Live data via Airtable API, proxied through a Cloudflare Worker
- Refreshes automatically every 5 minutes

## Tech stack

| Layer | Tool |
|---|---|
| Frontend | Vanilla HTML/CSS/JS, Chart.js |
| Data proxy | Cloudflare Workers |
| Data source | Airtable (WES master table) |
| Hosting | GitHub Pages |

## Security

- Password-protected (access code shared with contributors)
- CORS restricted to this GitHub Pages domain
- Airtable API key stored as Cloudflare Worker secret — never exposed in client code

## Built by

[Anubha Maneshwar](https://twitter.com/anubhamane4) — Founding Director, GS Labs / GirlScript Foundation · Program Delivery Lead, Protocol Labs (PLDG Cohort 6)

---

*This dashboard was built as part of the PLDG Cohort 6 wind-down. The program wrapped on March 27, 2026.*
