# Handwritten-Digit-Classification

## Overview

This project implements logistic regression classifiers to recognize handwritten digits using the MNIST dataset. It explores:
- Binary classification (digits 0 vs 1)
- Multiclass classification (digits 0–9, 8×8 images)
- Full MNIST 28×28 dataset
- Robust generalization under spurious correlations

## Key Insights
- Digits '8' are the hardest to classify correctly
- Logistic regression provides a strong linear baseline
- PCA and regularization improve generalization in high-dimensional data

## Dataset
- Original MNIST dataset (28×28 images) is automatically downloaded in the notebook
- Users can replace it with any compatible digit dataset by updating the data loading cells

## Technologies used
- Languages: Python
- Libraries: numpy, scikit-learn, matplotlib, pickle, tqdm
- Environment: Jupyter Notebook

## Running the Notebook
- The project is fully contained in a Jupyter Notebook. Run all cells sequentially to reproduce the analysis.
- The notebook automatically downloads the MNIST dataset for training and testing.
- 
## Testing and Evaluation
- The notebook includes evaluation on a separate test set to check model performance and robustness.
-Users can replace the default test set with their own data to see how the model generalizes.
-Accuracy and confusion matrices are computed automatically.
