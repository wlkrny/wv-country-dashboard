# Climate Negotiation Simulation Workshop

A single-file, offline-friendly scoreboard for a climate negotiation simulation workshop.

**Live demo:** https://wlkrny.github.io/wv-country-dashboard/

## What it does

- **Scoreboard** — track six countries across Tech, Budget, Governance, Labour, Emission, and Summit actions, with a running score per country.
- **Action Cards** — 15 preloaded cards (e.g. *Solar Farm Installation*, *Expand Coal-Fired Power Generation*) that apply resource gains/costs and emission changes with one click. Each card is editable.
- **Settlement** — enter goals achieved per country, then calculate individual, global (temperature-based), and total scores.
- **Workshop counters** — event, round, and summit numbers.
- State is saved to `localStorage`, so a refresh does not lose progress. Use **Reset values** to start over.

## Run locally

No build step, no dependencies:

```bash
open index.html
```

Or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

The site is hosted with GitHub Pages from the `main` branch root. Pushing to `main` redeploys automatically.

## License

MIT
