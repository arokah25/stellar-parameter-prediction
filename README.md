# Stellar Parameter Prediction with 1D CNN

This project uses a 1D Convolutional Neural Network to predict key stellar properties — effective temperature (T_eff), surface gravity (log_g), and metallicity ([Fe/H]) — from GALAH spectral data.

## Project Overview

Regression model implemented with PyTorch to extract stellar parameters spectral inputs. The improved version of the model also estimates predictive uncertainty under a Gaussian assumption.

## Files

- `stellar_1DCNN_regression.ipynb`:  
  Initial version – predicts T_eff, log_g, and [Fe/H] from GALAH spectra using a simple 1D CNN.
  
- `stellar_uncertainty_predictionCNN (2).ipynb`:  
  Improved version – predicts both parameter values and their Gaussian uncertainties.

- `data/`:  
  Directory for large `.npy` files. Not included due to size constraints.

- `CNNhelper.py/`: 
  Helper functions such as normalization, denormalization, train_NN, eval_NN, etc. 

### Data Sources

To run the model, download the data manually from:
- [spectra.npy](https://huggingface.co/datasets/simbaswe/galah4/blob/main/spectra.npy)  
- [labels.npy](https://huggingface.co/datasets/simbaswe/galah4/blob/main/labels.npy)

## How to Run

Run either notebook:
- In **Google Colab** (recommended for GPU access), or
- Locally with Python 3.x and PyTorch installed

## Requirements

- Python ≥ 3.8  
- PyTorch ≥ 1.10  
- NumPy  
- Matplotlib  
- scikit-learn

## Author

Adam Rokah  
Master’s student in Data Science, Uppsala University  
[LinkedIn](https://www.linkedin.com/in/adam-r-5a5b50135/)
