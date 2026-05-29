# Exploring the Stochastic World of SGD

This repository contains the implementation of the final project for the academic course **Stochastic Modelling and Simulations**.

The main objective of this project is to study the stochastic dynamics underlying **Stochastic Gradient Descent (SGD)** and some of its variants, such as **Mini-batch SGD** and **Stochastic Gradient Langevin Dynamics (SGLD)**.

---

## Project Structure

The project is divided into multiple sections.

### 1. Theory of SGD as an SDE

We derive the approximation of SGD and some of its variants as **Stochastic Differential Equations (SDEs)**.

### 2. Relevant Stochastic Properties

We compute and discuss several important stochastic properties of the SDE associated with SGD.

### 3. Visualization on Toy Landscapes

We visualize SGD and its stochastic behavior on simple optimization landscapes, such as the **Double Valley** potential.

### 4. Neural Network Experiments

We empirically test the stochastic properties discussed in the theoretical sections using a small neural network.

### 5. Comparison with Other Stochastic Optimization Techniques

We compare the stochastic behavior of SGD with other optimization techniques, such as:

* Swarm Optimization
* Simulated Annealing
* Langevin-based methods

---

## Repository Structure

```bash
├── figures/                       # Folder containg figures for notebooks
├── notebooks/                     # Folder containg notebooks
    ├── 01_theory.ipynb            # Sections 1 and 2
    ├── 02_visualization.ipynb     # Section 3
    ├── 03_nn_experiment.ipynb     # Section 4
    ├── 04_comparison.ipynb        # Section 5
├── references/                    # Folder containing various resources and references
├── README.md
└── requirements.txt
```

---

## Quick Setup

The repository includes a `requirements.txt` file.

It is strongly recommended to create a Python virtual environment using a Python version between **3.8** and **3.12** (inclusive), as these versions are generally more stable for scientific computing libraries.

Using the VS Code Jupyter Notebook interface to create the environment is recommended for simplicity. Alternatively, the environment can be created manually from the terminal.

```bash
# Windows only
py -3.12 -m venv .venv

# Activate the environment
.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

For Linux or macOS:

```bash
python3.12 -m venv .venv

source .venv/bin/activate

pip install -r requirements.txt
```

---

## References

The project is mainly inspired by literature on:

* SGD as an SDE approximation
* Langevin dynamics in optimization
* Stochastic optimization theory
* Diffusion-based interpretations of deep learning training
