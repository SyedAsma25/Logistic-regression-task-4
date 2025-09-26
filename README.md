---


```markdown
# Logistic Regression Project

This project applies **Logistic Regression** on the Breast Cancer dataset for binary classification (Malignant vs. Benign).

## Workflow
- Preprocess dataset (drop unnecessary columns, encode target)
- Train/test split (80/20)
- Standardize features
- Train Logistic Regression model
- Evaluate with confusion matrix, precision, recall, ROC-AUC
- Tune threshold and explain sigmoid function

## Run Instructions
1. Open `logistic_regression_classification.ipynb` in Jupyter
2. Run cells in order
3. View results (metrics, ROC curve, threshold effects)

## Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
