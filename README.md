# MNIST Multi-Class Classification with Gradient Descent Methods

This project implements a multi-class classifier for the MNIST dataset using three optimization techniques: Gradient Descent, Stochastic Gradient Descent (SGD), and Newton's Method. The goal is to train a model to recognize handwritten digits (0–9) using different optimization approaches to understand their effectiveness and behavior in multi-class classification.

## Project Overview

The classifier is trained on the MNIST dataset, a standard dataset of handwritten digits, with each optimizer applied separately to compare performance. The implemented optimizers are:
- **Gradient Descent**: Batch-based weight updates.
- **Stochastic Gradient Descent (SGD)**: Instance-based updates.
- **Newton's Method**: Second-order optimization for potentially faster convergence.

The project uses a linear model with a cross-entropy loss function for multi-class classification.

## Dependencies

- `torch` (for PyTorch operations)
- `torchvision` (for the MNIST dataset)
- `numpy`
- `matplotlib`

Install dependencies with:
```bash
pip install torch torchvision numpy matplotlib
