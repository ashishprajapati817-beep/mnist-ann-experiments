# MNIST Digit Classification — Baseline ANN (V1)

## Overview

A simple Artificial Neural Network (ANN) built on the MNIST dataset to establish a baseline performance.

---

## Model

* Input: 784 features (flattened 28×28 images)
* Hidden Layer: 128 neurons (ReLU)
* Output: 10 classes (Softmax)
* Optimizer: Adam
* Loss: Sparse Categorical Crossentropy

---

## Training

* Epochs: 10
* Validation: Test set

---

## Results

* ~97–98% validation accuracy
* Stable learning with slight overfitting

---

## Key Insight

Even a basic ANN performs strongly on MNIST, making it a good baseline for future improvements.

---

## Purpose of This Version

This baseline serves as a reference point for:

Comparing future improvements (Dropout, EarlyStopping, etc.)

Understanding model behavior before optimization 

## Next

Next version explores regularization (Dropout, EarlyStopping).
