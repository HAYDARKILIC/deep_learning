# Deep Learning Lecture Notebooks

** Haydar Kilic — Artificial Intelligence Engineering **
---

## Notebooks

| # | File | Topics |
|---|------|--------|
| 01 | `Lecture01_Introduction_Supervised_Learning.ipynb` | Learning paradigms (supervised / unsupervised / reinforcement), linear regression, gradient descent |
| 02 | `Lecture02_Shallow_and_Deep_Networks.ipynb` | Activation functions (ReLU / sigmoid / tanh), shallow networks, universal approximation theorem, deep networks |
| 03 | `Lecture03_Loss_Functions.ipynb` | MLE, MSE, MAE, Huber, Binary Cross-Entropy, Softmax + Cross-Entropy |
| 04 | `Lecture04_Training_Backpropagation.ipynb` | Backpropagation, chain rule, SGD, Adam, momentum, weight initialization |
| 05 | `Lecture05_Performance_Regularization.ipynb` | Bias-variance tradeoff, double descent, dropout, L1/L2, early stopping, batch normalization |
| 06 | `Lecture06_CNN_ResNet.ipynb` | 1D/2D convolution, padding, stride, pooling, LeNet, residual connections |
| 07 | `Lecture07_Transformers.ipynb` | Self-attention, multi-head attention, positional encoding, causal masking, Transformer block |
| 08 | `Lecture08_Generative_Models_GAN_VAE_Diffusion.ipynb` | GAN, mode collapse, VAE, ELBO, reparameterization trick, diffusion forward/reverse process |
| 09 | `Lecture09_Reinforcement_Learning.ipynb` | MDP, Q-learning, Bellman equation, epsilon-greedy, policy gradient (REINFORCE) |
| 10 | `Lecture10_Why_Deep_Learning_Works.ipynb` | Loss landscape, flat/sharp minima, overparameterization, implicit regularization, feature learning |
| 11 | `Lecture11_Graph_Neural_Networks.ipynb` | Graph representation, adjacency matrix powers, GCN, message passing, Kipf normalization, GAT |
| 12 | `Lecture12_Normalizing_Flows.ipynb` | Change of variables, Jacobian determinant, coupling flow, autoregressive flow, RealNVP, anomaly detection |

---

## Repository Structure

```
deep_learning/
├── README.md
├── requirements.txt
├── Lecture01_Introduction_Supervised_Learning.ipynb
├── Lecture02_Shallow_and_Deep_Networks.ipynb
├── Lecture03_Loss_Functions.ipynb
├── Lecture04_Training_Backpropagation.ipynb
├── Lecture05_Performance_Regularization.ipynb
├── Lecture06_CNN_ResNet.ipynb
├── Lecture07_Transformers.ipynb
├── Lecture08_Generative_Models_GAN_VAE_Diffusion.ipynb
├── Lecture09_Reinforcement_Learning.ipynb
├── Lecture10_Why_Deep_Learning_Works.ipynb
├── Lecture11_Graph_Neural_Networks.ipynb
└── Lecture12_Normalizing_Flows.ipynb
```

---

## Setup

**Requirements:** Python 3.10+

```bash
# 1. Clone the repository
git clone https://github.com/HAYDARKILIC/deep_learning.git
cd deep_learning

# 2. Create a virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

> **Note for Lecture 11 (GNN):** `torch-geometric` installation depends on your PyTorch and CUDA versions.  
> If the standard `pip install` fails, follow the official instructions at  
> https://pytorch-geometric.readthedocs.io/en/latest/install/installation.html

---

## Reference

Prince, S. J. D. (2023). *Understanding Deep Learning*. MIT Press.  
Available online: [https://udlbook.github.io/udlbook/](https://udlbook.github.io/udlbook/)

---
