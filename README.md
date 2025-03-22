# Customer Churn Analysis
This project analyzes customer churn behavior using a Telco dataset. The goal is to identify key drivers behind customer churn, build predictive models, and deliver actionable business recommendations.
---
## Objective

To perform in-depth data analysis and machine learning modeling to understand why customers leave a telecom company and how to predict churn efficiently.
---
## Project Structure
```
Customer_Churn_Analysis/
│
├── Data/                  # Raw dataset and processed data
├── Images/                # Visualizations and charts
├── Notebooks/             # Jupyter Notebook analysis
│   └── Customer_Churn_Analysis.ipynb
└── README.md              # Project documentation
```
---

## Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (Logistic Regression, Random Forest, SVC, KNN)
- **XGBoost** and **Gradient Boosting**
- **Jupyter Notebook** for analysis and visualization

---

## Key Insights

- **Top Features Impacting Churn**:
  - Low tenure, fiber optic internet, monthly charges, and absence of tech support/services significantly influence churn.
- **Best Performing Model**:
  - Gradient Boosting and XGBoost had the highest ROC-AUC scores, demonstrating strong predictive performance.
- **Churn Distribution**:
  - Around 26.49% of customers churned. This imbalance was addressed in evaluation metrics.
  - This indicates a significant retention challenge and highlights the importance of understanding customer behaviors to improve loyalty.

---

## Visualizations

- Correlation heatmap of top 15 features
- Feature importance charts (Logistic Regression & Tree-Based Models)
- ROC Curve comparison across all models
- Confusion matrices for all classifiers

---

## Business Recommendations

- **Customer Retention**: Focus on long-tenure incentives and bundled service discounts.
- **Tech Support**: Promote tech support plans as non-subscription is correlated with churn.
- **Pricing Strategy**: Re-evaluate pricing for customers with fiber optics or high monthly charges.

---

## Next Steps

- Perform hyperparameter tuning for best-performing models.
- Explore SHAP values for deeper model explainability.
- Deploy model via web dashboard for stakeholder use.

---

## Dataset

[Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## Author

Junghyun Cheon  
[GitHub](https://github.com/FEWDTC)


