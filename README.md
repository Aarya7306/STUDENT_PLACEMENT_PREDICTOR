# Student Placement Prediction - Machine Learning Project

This project develops and evaluates machine-learning models for student placement prediction.

## Project Structure

- `phase1/` - Simple linear regression analysis and feature weights.
- `phase2/` - Logistic regression classification with evaluation metrics, plots, and exported results.
- `phase3/` - Random Forest and XGBoost model training, evaluation, and feature importance analysis.
- `student_placement_phase1_ready.xlsx` - Prepared dataset used by the notebooks.

## Phase 2 Results

The Logistic Regression notebook generates:

- Accuracy, precision, recall, F1 score, and ROC-AUC metrics.
- A classification report.
- A confusion matrix.
- An ROC curve.
- Logistic-regression coefficient analysis.
- `phase2/logistic_regression_results.csv` containing the main evaluation metrics.

## How to Run

1. Open the required notebook in VS Code or Jupyter.
2. Select a Python kernel with the notebook dependencies installed.
3. Run the cells from top to bottom.

Run each phase from its own folder so that relative dataset paths resolve correctly.

## Phase 3 Results

Run the notebooks from the `phase3/` folder. Both models write their evaluation
metrics and feature-importance CSV files to `phase3/results/`:

- `random_forest_metrics.csv`
- `random_forest_feature_importance.csv`
- `xgboost_results.csv`
- `xgboost_feature_importance.csv`
