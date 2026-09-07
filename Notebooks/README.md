# Deep Learning 2026 — Lab Notebooks

Jupyter notebooks for the Deep Learning 2026 labs, one folder per topic and in
the order they are taught. Every notebook opens in Google Colab in one click —
no local install, no environment to set up.

Notebooks are stored **with their outputs**, so every plot and printed result is
visible on GitHub without running a single cell. Click **Open in Colab** when you
want to run or change something; edits there never touch this repository.

Where a topic has both a student and a solution notebook, work the student one
through to the end before opening the answers.

---

## Introduction to PyTorch

| Notebook | | Contents |
|---|---|---|
| [`Pytorch_coding_demonstration.ipynb`](1_Intro_to_pytorch/Pytorch_coding_demonstration.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/1_Intro_to_pytorch/Pytorch_coding_demonstration.ipynb) | Where PyTorch came from, how it is put together, and tensors worked through from first principles. |
| [`Pytorch_coding_demonstration.SOLUTION.ipynb`](1_Intro_to_pytorch/Pytorch_coding_demonstration.SOLUTION.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/1_Intro_to_pytorch/Pytorch_coding_demonstration.SOLUTION.ipynb) | Completed version of the Lab 0 demonstration. |

## Shallow Neural Networks

| Notebook | | Contents |
|---|---|---|
| [`XOR_Simple_Demo_Part1.ipynb`](2_Shallow_neural_networks/XOR_Simple_Demo_Part1.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/2_Shallow_neural_networks/XOR_Simple_Demo_Part1.ipynb) | The XOR problem: a single neuron always draws a straight line, so it cannot solve it. Why hidden layers exist. |
| [`Shallow_neural_networks_Part-2.ipynb`](2_Shallow_neural_networks/Shallow_neural_networks_Part-2.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/2_Shallow_neural_networks/Shallow_neural_networks_Part-2.ipynb) | Shallow networks with 1D inputs — one input, three hidden units, one output — and what changing the activation does. |

## Activation Functions

| Notebook | | Contents |
|---|---|---|
| [`Activation_Functions_Demo.ipynb`](3_Activation_Functions/Activation_Functions_Demo.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/3_Activation_Functions/Activation_Functions_Demo.ipynb) | One tiny 1 -> 3 -> 1 network with a different activation plugged in each time, so the change is attributable to the activation alone. |
| [`pytorch_forward_prop_and_loss.ipynb`](3_Activation_Functions/pytorch_forward_prop_and_loss.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/3_Activation_Functions/pytorch_forward_prop_and_loss.ipynb) | Forward propagation and loss on the Breast Cancer Wisconsin dataset. |

## Forward Propagation in PyTorch

| Notebook | | Contents |
|---|---|---|
| [`churn_forward_prop_and_loss_STUDENT.ipynb`](4_pytorch_forward_prop/churn_forward_prop_and_loss_STUDENT.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/4_pytorch_forward_prop/churn_forward_prop_and_loss_STUDENT.ipynb) | Forward pass and loss on the Bank Customer Churn dataset, with blanks to complete. |
| [`churn_forward_prop_and_loss_SOLUTION.ipynb`](4_pytorch_forward_prop/churn_forward_prop_and_loss_SOLUTION.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/4_pytorch_forward_prop/churn_forward_prop_and_loss_SOLUTION.ipynb) | Completed version of the churn forward-propagation lab. |

## Loss Functions

| Notebook | | Contents |
|---|---|---|
| [`Loss_Functions_LAB4.ipynb`](5_Loss_Functions/Loss_Functions_LAB4.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/5_Loss_Functions/Loss_Functions_LAB4.ipynb) | Three losses built by hand and checked against PyTorch: MSE for regression, BCE for binary, cross-entropy for multi-class. |
| [`Loss_Functions_Exercise.ipynb`](5_Loss_Functions/Loss_Functions_Exercise.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/5_Loss_Functions/Loss_Functions_Exercise.ipynb) | Turning "how wrong" into a single number, and choosing the loss that matches the task. |
| [`Loss_Functions_Exercise_Solution.ipynb`](5_Loss_Functions/Loss_Functions_Exercise_Solution.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/5_Loss_Functions/Loss_Functions_Exercise_Solution.ipynb) | Completed version of the loss-functions exercise. |

## Autograd

| Notebook | | Contents |
|---|---|---|
| [`pytorch_autograd_Part1.ipynb`](6_Auto_grad/pytorch_autograd_Part1.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/6_Auto_grad/pytorch_autograd_Part1.ipynb) | The computational graph, `requires_grad`, `.backward()`, and the chain rule applied automatically. |
| [`PyTorch_Autograd_Exercise.ipynb`](6_Auto_grad/PyTorch_Autograd_Exercise.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/6_Auto_grad/PyTorch_Autograd_Exercise.ipynb) | Computing gradients with autograd instead of differentiating by hand. |

## Training Pipeline

| Notebook | | Contents |
|---|---|---|
| [`pytorch_training_pipeline.ipynb`](7_pytorch_training_pipeline/pytorch_training_pipeline.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/7_pytorch_training_pipeline/pytorch_training_pipeline.ipynb) | A binary classifier built from the ground up on the Pima Indians Diabetes dataset. |
| [`lab_pytorch_nn_module_breast_cancer_PRACTICE.ipynb`](7_pytorch_training_pipeline/lab_pytorch_nn_module_breast_cancer_PRACTICE.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/7_pytorch_training_pipeline/lab_pytorch_nn_module_breast_cancer_PRACTICE.ipynb) | Backpropagation and autograd inside a complete training loop, using `nn.Module`. |

## Gradient Descent and Its Types

| Notebook | | Contents |
|---|---|---|
| [`Gradient_Descent_Types.ipynb`](8_Gradient_Descent_Types/Gradient_Descent_Types.ipynb) | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">](https://colab.research.google.com/github/sparshbansal-newton/deep-learning-labs/blob/main/Notebooks/8_Gradient_Descent_Types/Gradient_Descent_Types.ipynb) | The same network trained three times, changing only `batch_size` — batch, stochastic and mini-batch compared. |

Folder `3_Activation_Functions` also holds [`activation_functions_Visualization.html`](3_Activation_Functions/activation_functions_Visualization.html), a standalone page that plots each activation and its derivative.

---

The browser-based interactive labs live at the repository root and are indexed on
the [live site](https://sparshbansal-newton.github.io/deep-learning-labs/).
