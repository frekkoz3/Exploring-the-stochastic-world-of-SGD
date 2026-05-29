# Exploring the Stochastic World of SGD

This repo contains the implementation of the final project for the academic course "Stochastic Modelling and Simulations".

The main objective of this project is to study the stochastic dynamics undergoing **Stochastic Gradient Descent** (**SGD**) and some of its variants, such as **Minibatch SGD** or **Stochastic Gradient Langevin Dynamic** (**SGLD**).

## Sections Stucture

The project will be divided in multiple sections.

1. **Theory of SGD as SDE**
    We will obtain the formulation of the SGD and some of its variants as a *Stochastic Differential Equation* (SDE).
2. **Relevant Stochastic Properties**
    We will compute and discuss some essential *stochastic properties* of the SGD's SDE.
3. **Visulazion on Toy Landscape**
    We will visualize the SGD (and its stochastic properties) on some toy landscape, such as *Double Valley*.
4. **Neural Network Experiment**
    We will statistically test the desired stochastic properties on a little *Neural Network*.
5. **Comparison against other Stochastic Optimization Techniques**
    We will discuss the difference between stochastic properties of SGD and other optimization techniques, such as *Swarm Optimization* or *Simulated Annealing*.

## Repo Structure

```bash
├── 1 theory.ipynb            # notebook implementing section 1 and section 2
├── 2 visualization.ipynb     # notebook implementing section 3
├── 3 nn experiment.ipynb     # notebook implementing section 4
├── 4 comparison.ipynb        # notebook implementing section 5
├── READEME.md
└── requirements.txt
```

## Quick setup

The repo contains a `requirements.txt`.
It is strongly suggest to create a python virtual environment with **python version >= 3.8 and <= 3.12** (usually more stable).
It is also strongly suggested to create the environment directly from the VS code jupyter notebook interface (in order to make it easier).
If this is not possible, just paste the following lines in the terminal.

```bash
# Windows only
py -3.12 -m venv .venv
.venv\script\activate
pip install -r requirements.txt
```
