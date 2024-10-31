# HW4 - Parameter Tuning and Select Best Model

This project compares three regression models (**Linear Regression**, **Lasso**, and **Ridge**) for predicting bicycle traffic based on given features from Regularization Jupyter Notebook. The model performance is then evaluated using 10-fold cross-validation, and the best model is selected based on cross-validation scores. Tuning for `alpha` is performed on the `Lasso` and `Ridge` models using `RandomizedSearchCV`.

## Team Members
- **Tyler Braxton** - braxtonc18@students.ecu.edu
- **Christian Grandy** - grandyc21@students.ecu.edu

## CV Scores/ Alpha Value
- **Linear Regression** - 0.769175/ None
- **Lasso** -             0.771242/ 10.0
- **Ridge** -             0.773031/ 100.0

## Which Model performed the Best?
**Ridge**

## Instructions to Run
Make sure data file from Regression Notebook is in Same file as this HW
Run Notebook code cells
If a module is not installed then pip install as needed