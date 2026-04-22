# HEART Metrics

AI that helps managers retain top talent. HEART Metrics turns everyday employee signals into early burnout warnings so managers can intervene before good people leave.

**Live demo:** [https://heartmetrics.us](https://heartmetrics.us)

## About

HEART Metrics combines four dimensions of work wellbeing into a single Work Wellbeing Index (WWI) per employee:

- **Workload** — WIP, meeting load, blocked items, after-hours work
- **Recognition** — public and private recognition events
- **Feedback** — 1:1 cadence and feedback quality
- **Growth** — strategic vs. tactical work distribution

Managers see who needs attention, why, and what actions to take — grounded in real team signals rather than generic surveys.

## Stack

Single-file HTML prototype. React 18 + Tailwind CSS + Recharts-free SVG charts, loaded via CDN. No build step required.

All employee data in the live demo is **synthetic** and for illustration purposes only.

## Run locally

Clone the repo and open `index.html` in any modern browser:

```bash
git clone https://github.com/vipulrfid/heartmetrics.git
cd heartmetrics
open index.html
```

## Hosting

This site is deployed on GitHub Pages with a custom domain. The `CNAME` file configures the `heartmetrics.us` domain mapping.

---

© 2026 HEART Metrics. Prototype build.
