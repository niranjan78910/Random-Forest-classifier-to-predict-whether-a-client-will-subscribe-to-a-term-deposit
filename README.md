# Bank Marketing — Term Deposit Subscription Prediction

A machine-learning notebook exploring whether a bank customer will subscribe to a term deposit.

## Repository files

- `bank_marketing.ipynb`: analysis and modelling notebook
- `bank-additional-full.csv`: dataset included with the repository
- `bank-additional-names.txt`: dataset field descriptions
- `preprocessor.pkl`: serialised preprocessing artefact

## Reproduce the analysis

1. Create a Python virtual environment.
2. Open `bank_marketing.ipynb` with Jupyter Notebook or JupyterLab.
3. Review and install the libraries imported by the notebook.
4. Run notebook cells in order and record the final evaluation results.

> This repository does not yet include a dependency lockfile or a verified end-to-end reproduction procedure. The notebook's outputs have not been independently validated in this review.

## Suggested evaluation

For an imbalanced binary-classification problem, report precision, recall, F1, confusion matrix and ROC-AUC where applicable. Compare against a simple baseline, and make sure preprocessing is fit on training data only.

## Next improvements

- [ ] Add a reproducible `requirements.txt` or environment file.
- [ ] Explain the data source and redistribution permissions.
- [ ] Record the model's actual held-out evaluation metrics.
- [ ] Clarify how missing values, categorical features and class imbalance are handled.
- [ ] Add a clean results summary and figures.
- [ ] Add automated tests for preprocessing and inference.

## Scope

Educational classification project; predictions should not be used to make real banking decisions without additional validation and governance.
