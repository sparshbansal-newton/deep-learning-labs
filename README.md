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
| [`01_Intro_to_pytorch`](Notebooks/01_Intro_to_pytorch) | PyTorch history, architecture and tensors |
| [`02_Shallow_neural_networks`](Notebooks/02_Shallow_neural_networks) | XOR, and shallow networks with 1D inputs |
| [`03_Activation_Functions`](Notebooks/03_Activation_Functions) | Activations compared on one fixed network |
| [`04_pytorch_forward_prop`](Notebooks/04_pytorch_forward_prop) | Forward propagation and loss (bank churn) |
| [`05_Loss_Functions`](Notebooks/05_Loss_Functions) | MSE, BCE and cross-entropy, built by hand |
| [`06_Auto_grad`](Notebooks/06_Auto_grad) | The computational graph and `.backward()` |
| [`07_pytorch_training_pipeline`](Notebooks/07_pytorch_training_pipeline) | A full training loop with `nn.Module` |
| [`08_Gradient_Descent_Types`](Notebooks/08_Gradient_Descent_Types) | Batch, stochastic and mini-batch compared |
| [`09_Optimizers`](Notebooks/09_Optimizers) | SGD, momentum, NAG, AdaGrad, RMSProp and Adam compared |
| [`10_Dataset_DataLoader`](Notebooks/10_Dataset_DataLoader) | `Dataset` and `DataLoader` built and traced on a toy set |

Outputs are kept in the committed notebooks, so plots and printed results render
on GitHub without running anything.

## Will be adding more interactive lab and Notebooks in Future

