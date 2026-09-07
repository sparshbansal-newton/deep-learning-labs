# Deep Learning 2026 — Interactive Labs

Laboratory exercises for the Deep Learning 2026 course. Each lab is a single
self-contained HTML page that runs entirely in the browser: no installation,
no server, and no external data to download.

**Live site:** https://sparshbansal-newton.github.io/deep-learning-labs/

## Labs

| Lab | Topic | Covers |
|-----|-------|--------|
| Gradient Descent | [gradient-descent-lab.html](gradient-descent-lab.html) | Batch, stochastic and mini-batch regimes; epochs; convergence path; memory cost |
| Data Pipeline | [dataset-dataloader-lab.html](dataset-dataloader-lab.html) | `Dataset`, `DataLoader`, transforms, samplers, `collate_fn`, `num_workers` |

## Adding a lab

1. Place the new `.html` file in the repository root.
2. In `index.html`, copy the commented card template above the lab list, paste
   it inside `<section class="labs">`, and edit the link, kicker, title,
   summary, tags and footer fields.

Lab numbers and the two on-page counts are derived from the list at render
time, so no other text in `index.html` needs to be changed.
