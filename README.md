# FloodPrediction
Contains code for a Stacking Ensemble model that predicts flood probability using a combination of tree-based regression models and a PyTorch perceptron as a meta-learner. The model was developed for a Kaggle Playground Competition.

# Flood Probability Prediction with Stacking Ensemble

This repository implements a Stacking Ensemble model for predicting flood probability from a given dataset. The model leverages the strengths of different tree-based regression methods (XGBoost, CatBoost, LightGBM) as base learners and combines their predictions using a PyTorch perceptron as a meta-learner.

# Getting Started

Clone this repository.
Install required libraries (scikit-learn, xgboost, catboost, lightgbm, torch).
Ensure you have the competition dataset available and structured as required by the code.
Run the Jupyter notebook (flood-prediction-using-regression.ipynb) to train and evaluate the model.
Model Architecture:

Base Learners:
* XGBoost Regressor
* CatBoost Regressor
* LightGBM Regressor
  
Meta-Learner:
 * PyTorch Perceptron
   
flood-prediction-using-regression .ipynb: Jupyter notebook containing the complete code for training and evaluation.

This code provides a basic implementation of a stacking ensemble with a perceptron meta-learner. You can explore further improvements by:

Trying different hyperparameter tuning techniques for the base learners and meta-learner.
Experimenting with different meta-learner architectures (e.g., deeper neural networks).
Including additional features or data preprocessing steps for better performance.
Feel free to fork this repository and contribute your own enhancements!
