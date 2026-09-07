# Deep Learning 2026 — Interactive Labs

Laboratory exercises for the Deep Learning 2026 course. Each lab is a single
self-contained HTML page that runs entirely in the browser: no installation,
no server, and no external data to download.

**Live site:** https://sparshbansal-newton.github.io/deep-learning-labs/

## Labs

| # | Lab | Covers |
|-----|-------|--------|
| Lab 06 | [Gradient Descent and Its Types](gradient-descent-lab.html) | Batch, stochastic and mini-batch regimes in PyTorch; loss curves; optimisation path; vectorisation vs. memory |
| Lab 07 | [Datasets and DataLoaders in PyTorch](dataset-dataloader-lab.html) | `Dataset`, `DataLoader`, transforms, samplers, `collate_fn`, `num_workers` |

## Adding a lab

1. Place the new `.html` file in the repository root.
2. In `index.html`, copy the commented `<li>` template above the list, paste
   it inside `<ol class="list">`, and edit the link, tag, title, summary and
   covers line.

The page states no counts or totals, so nothing outside the pasted block
ever needs to be edited.
