# MNIST Digit Classification — Deeper ANN (V3)

## Overview

This version investigates the effect of increasing model depth on performance.

A deeper neural network is introduced to analyze how additional layers impact learning and generalization.

---

## Model

* Architecture: 2 hidden layers (256 → 128 neurons)
* Activation: ReLU
* Output: Softmax (10 classes)
* Optimizer: Adam (learning rate = 0.001)

---

## Training

* Epochs: 20
* Batch Size: 32
* No regularization applied

---

## Results

* Training accuracy: >99%
* Validation accuracy: ~97–98%
* Validation loss increases after early epochs

---

## Key Insight

Increasing depth improves training performance but leads to early overfitting.

Best generalization occurs around epoch 5–7.

---

## Learning Outcome

This experiment demonstrates that higher model capacity must be controlled to avoid overfitting.

---

## Next Step

Introduce techniques like EarlyStopping or improved architectures to control overfitting.
