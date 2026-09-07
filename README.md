# Deep Learning 2026 — Labs

Laboratory material for the Deep Learning 2026 course, in two forms: **interactive
lab pages** that run entirely in the browser, and **Jupyter notebooks** that open
in Google Colab in one click.

**Live site:** https://sparshbansal-newton.github.io/deep-learning-labs/

## Interactive labs

Single self-contained HTML pages: no installation, no server, no external data.

| # | Lab | Covers |
|-----|-------|--------|
| Lab  | [Gradient Descent and Its Types](gradient-descent-lab.html) | Batch, stochastic and mini-batch regimes in PyTorch; loss curves; optimisation path; vectorisation vs. memory |
| Lab  | [Datasets and DataLoaders in PyTorch](dataset-dataloader-lab.html) | `Dataset`, `DataLoader`, transforms, samplers, `collate_fn`, `num_workers` |

## Notebooks

Jupyter notebooks, one folder per topic, in teaching order. The full index with
per-notebook Colab links is in [`Notebooks/README.md`](Notebooks/README.md).

| Folder | Topic |
|---|---|
| [`1_Intro_to_pytorch`](Notebooks/1_Intro_to_pytorch) | PyTorch history, architecture and tensors |
| [`2_Shallow_neural_networks`](Notebooks/2_Shallow_neural_networks) | XOR, and shallow networks with 1D inputs |
| [`3_Activation_Functions`](Notebooks/3_Activation_Functions) | Activations compared on one fixed network |
| [`4_pytorch_forward_prop`](Notebooks/4_pytorch_forward_prop) | Forward propagation and loss (bank churn) |
| [`5_Loss_Functions`](Notebooks/5_Loss_Functions) | MSE, BCE and cross-entropy, built by hand |
| [`6_Auto_grad`](Notebooks/6_Auto_grad) | The computational graph and `.backward()` |
| [`7_pytorch_training_pipeline`](Notebooks/7_pytorch_training_pipeline) | A full training loop with `nn.Module` |
| [`8_Gradient_Descent_Types`](Notebooks/8_Gradient_Descent_Types) | Batch, stochastic and mini-batch compared |

Outputs are kept in the committed notebooks, so plots and printed results render
on GitHub without running anything.

## Adding an interactive lab

1. Place the new `.html` file in the repository root.
2. In `index.html`, copy the commented `<li>` template above the list, paste
   it inside `<ol class="list">`, and edit the link, tag, title, summary and
   covers line.

The page states no counts or totals, so nothing outside the pasted block
ever needs to be edited.

## Adding a notebook

1. Drop the `.ipynb` file into the right `Notebooks/<n>_<topic>/` folder.
2. Give it a first markdown cell holding the Colab badge, with cell metadata
   `{"id": "view-in-github", "colab_type": "text"}`, and set
   `metadata.colab.include_colab_link` to `true` in the notebook. The badge href is
   `https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/<folder>/<file>.ipynb`.
3. Add a row to the matching table in `Notebooks/README.md`.
