# Collectibles Market

A landscape and player map for the global collectibles category, zoomed from world to Asia to Southeast Asia to Indonesia. Every number carries a confidence rating so nothing gets quoted downstream that cannot be defended.

Live: https://collectibles-market-report.vercel.app

## What it argues

Growth sits in the secondary market and the trust layer, not in making new objects. The five-layer stack [IP, manufacture, retail, liquidity, trust] has only two profitable seats and one of them is closed to new entrants. For Indonesia the finding is that demand is proven and the trust layer is contested but not yet won.

## Stack

Single static `index.html`. Chart.js from CDN, no build step, no dependencies.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy

Hosted on Vercel as the `collectibles-market-report` project.

```
npx vercel deploy --prod --yes
```

`.vercel/` is gitignored - run `vercel link` to reconnect a fresh clone. Only ever deploy this subfolder, never the repo root.

## Revision log

**Revision 2 - August 2026.** Deeper research pass. Corrected the claim that Indonesia has zero grading labs [EGS and ZMG both operate]. Added the full Indonesian grading cost ladder in rupiah, PSA's 2026 capacity crisis and backlog tracker, Indonesia Card Party as community evidence, Nimitz Cards as proof of submission volume, and updated Kayou and Top Toy IPO status. Verdict shifted from "claim the empty trust layer" to "own measurement, then trust."

**Revision 1 - August 2026.** Initial landscape, player map and Indonesia zoom.

## Notes

- Source of truth for this project is this folder. `Outputs/Collectibles_Report.html` is a mirrored copy kept for the Outputs convention.
- Rupiah grading prices float with USD/IDR and brokers revise them upward as the rupiah weakens. Treat them as an August 2026 snapshot and re-pull before quoting.
