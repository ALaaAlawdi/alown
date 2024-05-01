
# ML Project Final

This is the code for the final project in the machine learning course. It includes pre-processing, feature extraction, data analysis, and machine learning algorithm experimentation.

## Instructions

1. Clone the repository.
2. Install the necessary dependencies (`pandas`, `matplotlib`, `seaborn`, `numpy`, `scipy`, `scikit-learn`, `xgboost`, `mlxtend`, `lightgbm`).
3. Run the Jupyter notebook `ML_Project_Final.ipynb`.

## Pre-processing

- Imputation of missing values.
- Transformation of target variable.
- Engineering of new features.

## Feature Extraction

- Use of statistical methods like Box-Cox transformation.
- Standardization of numeric features.
- One-hot encoding of categorical features.

## Data Analysis

- Exploration of the target variable distribution.
- Identification and removal of outliers.
- Visualization of key features.

## Machine Learning Algorithm Experimentation

- Training of various models (Ridge, Lasso, SVR, LGBM, GBM).
- Hyperparameter tuning using random search.
- Stacking of models for ensemble prediction.

## Results and Analysis

- Evaluation of model performance using RMSE.
- Comparison of individual models and stacked ensemble.

The final RMSE value is 0.3848, calculated using `rmse(np.log(y_true),preds)`.
