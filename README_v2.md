# MNIST ANN Study (V1 → V2)

## Goal

Understand how regularization techniques affect model performance.

## V1: Baseline Model

* 1 hidden layer (128 neurons)
* ReLU activation
* No regularization

## V2: Dropout + EarlyStopping

* 1 hidden layer (256 neurons)
* Dropout (0.2) added to reduce overfitting
* EarlyStopping used to stop training when validation loss stops improving

## Observations

* EarlyStopping stopped training around 8-10 epochs
* Dropout slightly reduced overfitting
* Validation accuracy remained stable (~98%)

## Files

* v1_ann_baseline.ipynb
* v2_dropout_earlystop.ipynb
