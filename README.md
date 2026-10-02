# Student Placement Prediction - Machine Learning Project

This project develops and evaluates machine-learning models for student placement prediction.

## Project Structure

- `phase1/` - Simple linear regression analysis and feature weights.
- `phase2/` - Logistic regression classification with evaluation metrics, plots, and exported results.
- `phase4/` - XGBoost model training, evaluation, and feature importance analysis.
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
