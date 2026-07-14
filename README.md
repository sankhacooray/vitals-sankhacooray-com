# vitals

A personal field journal — Sankha Cooray's notes on intermittent fasting,
autophagy, lean-mass hyper-responder profile, and self-tracked metabolic
experiments.

Deployed at **[vitals.sankhacooray.com](https://vitals.sankhacooray.com)** via
GitHub Pages.

## Sections

1. **About** — quiet, long-running self-experiment
2. **What I Actually Do** — eating window, training, tracking
3. **Self-Studies from Lab Reports** — LMHR phenotype, glucose/HbA1c, body comp
4. **Working Beliefs** — autophagy, real food, n=1 learning

## Files

| File | Purpose |
|------|---------|
| `index.html` | Single-file site, all CSS inline |
| `CNAME` | GitHub Pages custom-domain pointer |

## Live data

The **Live Signal** section pulls a curated JSON snapshot from a private Apps
Script proxy (see `withings-body-scan/apps-script/` in the sclab workspace):

- **Body Scan** metrics render in `#live-data` (vitality, vascular age, rings).
- **ScanWatch 2** metrics render in `#watch-data` when the payload carries a
  `watch` block (sleep score/hours, night HR, respiratory rate, steps, SpO₂).
  Until then the section shows the "arrived · syncing up" teaser; JS flips it
  to a live grid automatically once watch data flows.

## Next steps

- [ ] Write up each self-study card (replace "write-up coming" links)
- [ ] Add a longitudinal chart (lipid panels / body comp) when data is ready
