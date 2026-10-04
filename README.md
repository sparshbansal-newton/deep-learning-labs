# Deep Learning 2026 — Laboratory Materials

Laboratory material for the Deep Learning 2026 course, in two forms: **Jupyter
notebooks** that open in Google Colab in one click, and **interactive lab pages**
that run entirely in the browser. Material is organised into four units and
numbered by topic in teaching order.

**Live site:** https://sparshbansal-newton.github.io/deep-learning-labs/

## Course outline

| Unit | Theme | Topics |
|---|---|---|
| I | Foundations of PyTorch and Neural Networks | 01–07 |
| II | Optimisation and Data Pipelines | 08–10 |
| III | Regularisation | 11 |
| IV | Convolutional Neural Networks | 12–13 |

## Notebooks

One folder per topic. The full index, with a Colab link for every notebook, is in
[`Notebooks/README.md`](Notebooks/README.md). Outputs are kept in the committed
notebooks, so plots and printed results render on GitHub without running anything.

### Unit I — Foundations of PyTorch and Neural Networks

| Topic | Folder | Contents |
|---|---|---|
| 01 | [`01_Intro_to_pytorch`](Notebooks/01_Intro_to_pytorch) | PyTorch history, architecture and tensors |
| 02 | [`02_Shallow_neural_networks`](Notebooks/02_Shallow_neural_networks) | XOR, and shallow networks with 1D inputs |
| 03 | [`03_Activation_Functions`](Notebooks/03_Activation_Functions) | Activations compared on one fixed network |
| 04 | [`04_pytorch_forward_prop`](Notebooks/04_pytorch_forward_prop) | Forward propagation and loss (bank churn) |
| 05 | [`05_Loss_Functions`](Notebooks/05_Loss_Functions) | MSE, BCE and cross-entropy, built by hand |
| 06 | [`06_Auto_grad`](Notebooks/06_Auto_grad) | The computational graph and `.backward()` |
| 07 | [`07_pytorch_training_pipeline`](Notebooks/07_pytorch_training_pipeline) | A full training loop with `nn.Module` |

### Unit II — Optimisation and Data Pipelines

| Topic | Folder | Contents |
|---|---|---|
| 08 | [`08_Gradient_Descent_Types`](Notebooks/08_Gradient_Descent_Types) | Batch, stochastic and mini-batch compared |
| 09 | [`09_Optimizers`](Notebooks/09_Optimizers) | SGD, momentum, NAG, AdaGrad, RMSProp and Adam compared |
| 10 | [`10_Dataset_DataLoader`](Notebooks/10_Dataset_DataLoader) | `Dataset` and `DataLoader` built and traced on a toy set |

### Unit III — Regularisation

| Topic | Folder | Contents |
|---|---|---|
| 11 | [`11_Regularization`](Notebooks/11_Regularization) | L2 weight decay, then Dropout and BatchNorm, against overfitting |

### Unit IV — Convolutional Neural Networks

| Topic | Folder | Contents |
|---|---|---|
| 12 | [`12_CNN`](Notebooks/12_CNN) | A CNN on CIFAR-10, then BatchNorm and Dropout to close the overfitting gap |
| 13 | [`13_CNN_Architectures`](Notebooks/13_CNN_Architectures) | CNN, AlexNet, VGG and ResNet-18 compared on CIFAR-10 |

## Interactive labs

Single self-contained HTML pages that accompany a topic: no installation, no server,
no external data.

| Topic | Lab | Covers |
|---|---|---|
| 08 | [Gradient Descent and Its Types](gradient-descent-lab.html) | Batch, stochastic and mini-batch regimes in PyTorch; loss curves; optimisation path; vectorisation vs. memory |
| 10 | [Datasets and DataLoaders in PyTorch](dataset-dataloader-lab.html) | `Dataset`, `DataLoader`, transforms, samplers, `collate_fn`, `num_workers` |

## Core texts

- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press. [deeplearningbook.org](https://www.deeplearningbook.org/)
- Prince, S. J. D. (2023). *Understanding Deep Learning*. MIT Press. [udlbook.github.io](https://udlbook.github.io/udlbook/)
- Zhang, A., Lipton, Z. C., Li, M., & Smola, A. J. (2023). *Dive into Deep Learning*. Cambridge University Press. [d2l.ai](https://d2l.ai/)

Topic-specific papers are listed in a **References** section at the end of each
notebook that follows published work.

## Citation

If you use this material, please cite it via **Cite this repository** in the
GitHub sidebar (generated from [`CITATION.cff`](CITATION.cff)).

## License

Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE):
you may share and adapt the material, including commercially, with attribution.
