# Customer Churn Prediction

A machine learning project that predicts if a customer will leave a service (churn).
Built by Hemanth Ponraj — Georgia State University.

## What It Does
- Cleans and prepares the Telco Customer Churn dataset
- Trains 4 models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
- Uses cross-validation to test each model
- Best model got 80% accuracy and 0.835 ROC-AUC score

## Tools Used
- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- matplotlib, seaborn

## How to Run
1. Install the packages:pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
2. Open `ML_Project-2.ipynb` in Jupyter Notebook
3. Run all cells top to bottom

## Files
| File | What it is |
|------|------------|
| `ML_Project-2.ipynb` | Main project notebook |
| `ML_REPORT.docx` | Full research report |

## Results
| Model | ROC-AUC |
|-------|---------|
| Gradient Boosting | 0.8484 |
| Logistic Regression | 0.8482 |
| Random Forest | 0.8253 |
| Decision Tree | 0.6536 |
