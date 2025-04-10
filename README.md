# stellar-parameter-prediction
Predicting stellar properties (T_eff, log_g, [Fe/H]) from GALAH spectra using a 1D Convolutional Neural Network.

# Stellar Parameter Prediction with CNN

This project uses a 1D Convolutional Neural Network to predict stellar parameters (`T_eff`, `log_g`, `[Fe/H]`) from GALAH spectral data.

## Files

- `stellar_1DCNN_regression.ipynb`: 1st iteration -- simple NN regression prediction features (temperature, gravity, metallicity) from stellar-emission spectra.
- 'stellar_uncertainty_predictionCNN (2).ipynb': improved model + also predicting uncertainties around the estimates (assumption: uncertainties follows Gaussian distribution)
- `data/`: raw `.npy` files (not uploaded — too large). Download from:
- https://huggingface.co/datasets/simbaswe/galah4/blob/main/spectra.npy
- https://huggingface.co/datasets/simbaswe/galah4/blob/main/labels.npy

## How to Run
Run in Google Colab or locally with Python and PyTorch.

## Contact
Made by Adam Rokah — master's student @ Uppsala University
