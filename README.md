# Customer Churn Prediction & Retention Analytics

An end-to-end Kaggle/Jupyter notebook for a realistic business analytics problem: exploring subscription customer churn, training machine-learning models, evaluating performance, and creating a ranked review list for supportive retention outreach.

## Features
- Data loading and validation
- Exploratory analysis and churn-rate summaries
- Missing-value handling and categorical encoding
- Scikit-learn preprocessing pipeline
- Baseline, logistic regression, and random forest comparison
- Accuracy, precision, recall, F1, ROC-AUC and classification report
- Confusion matrix, ROC curve and precision-recall curve
- Churn-risk review CSV and model metrics export
- Responsible-use discussion

## Dataset
Use an authorized copy of the IBM Telco Customer Churn sample dataset from Kaggle or another source whose terms permit your intended use. This repository does not include customer data. Attach the dataset in Kaggle and update `DATA_PATH` to the exact CSV path shown in the Input panel.

## Run in Kaggle
1. Create a new notebook or import `customer_churn_prediction.ipynb`.
2. Use **Add Input** to attach the dataset.
3. Update `DATA_PATH` near the top of the notebook.
4. Run all cells.
5. Review actual metrics and download CSV outputs from the notebook output panel.

## Methodology note
For simplicity, the notebook demonstrates selecting the highest-F1 model from the comparison table. A rigorous workflow should choose the model using a validation split or cross-validation, then evaluate the held-out test set only once. Do not claim performance values until the notebook has been run.

## Responsible use
Predicted risk is uncertain. Use it to prioritize helpful retention support, not to deny service or set unfair prices. Review privacy, subgroup performance, and human oversight before deployment.

## GitHub description
End-to-end customer churn analytics and machine learning project using Python, scikit-learn, and retention risk analysis.
