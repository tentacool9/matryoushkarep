# Convolutional Neural Network (CNN) vs. Matryoshka Representation Learning (MRL) CNN: Comparative Analysis On MNIST

This repository contains a Jupyter notebook that compares a native CNN and an MRL-CNN across 50 experiments, analyzing performance, robustness, and interpretability.

## Overview
The study conducts 50 experiments to evaluate:
Accuracy/loss metrics on MNIST/CIFAR-10.
Class-wise cosine similarity of embeddings.
Grad-CAM feature importance maps.
Robustness against MNIST-C corruptions.
Eigenvalue distributions of linear layers.

## Key Features

* 50 trials with statistical reporting (mean/variance).

* Cosine similarity analysis of intra/inter-class embeddings.

* Visual comparison of Grad-CAM attention regions.

* MNIST-C corruption tests (noise, blur, rotation).

* Eigenvalue diagnostics for layer stability.

---
Matryoshka Representation Learning: https://arxiv.org/abs/2205.13147

MNIST-C: https://github.com/google-research/mnist-c
