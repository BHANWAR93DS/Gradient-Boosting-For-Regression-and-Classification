# Gradient Boosting for Regression & Classification

A hands-on study of Gradient Boosting using synthetic regression and classification problems, focused on stage-wise learning and the effect of model complexity.

## What This Project Demonstrates

- Synthetic-data generation
- Decision trees as weak learners
- Gradient Boosting for regression
- Gradient Boosting for classification
- Stage-wise prediction refinement
- Residual/probability analysis
- Underfitting vs overfitting
- Visual model interpretation

## Notebooks

| Notebook | Focus |
|---|---|
| Gradient_Boosting_Regression.ipynb | Gradient Boosting Regressor on noisy quadratic data |
| Gradient_Boost_Classification_1.ipynb | Gradient Boosting Classifier and classification analysis |

## Core Idea

~~~text
Initial prediction
      ↓
Measure error
      ↓
Fit weak learner to error
      ↓
Update ensemble
      ↓
Repeat
~~~

## Tech Stack

Python · NumPy · Pandas · Scikit-learn · Matplotlib · Seaborn

## Run

~~~bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook
~~~

## Future Improvements

- Reproducible requirements.txt
- Random Forest comparison
- Hyperparameter tuning
- Cross-validation
- Standardized evaluation metrics
- Learning-curve analysis

**Skills:** Ensemble Learning · Regression · Classification · Model Diagnostics
