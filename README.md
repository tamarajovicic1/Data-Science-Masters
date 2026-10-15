# Data Science MSc Projects

Projects from my Master's in Data Science at Singidunum University (2024–2025), covering the full data workflow: data cleaning, exploratory analysis, feature engineering, model training and evaluation, and model explainability.

**Tools:** Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, SHAP

## Projects

| Project | Description | Methods | Result |
|---|---|---|---|
| [**MSc Thesis: Breast Cancer Classification**](msc-thesis-breast-cancer-classification/) | Classifies breast tumors as malignant or benign from cell nucleus measurements (Wisconsin Breast Cancer dataset, 569 samples). | Linear & Logistic Regression, Random Forest, stratified 10-fold cross-validation, scaling inside a pipeline | Logistic Regression: **97.5% ± 2.0%** CV accuracy |
| [**Breast Cancer Data Preparation**](breast-cancer-analysis/) | Data cleaning, exploratory analysis and feature engineering on the same dataset. | Correlation analysis, z-score outlier detection, new features, Random Forest feature importance | Identified the strongest predictors of malignancy |
| [**Heart Disease Prediction**](heart-disease-prediction/) | Predicts the presence of heart disease from clinical parameters (918 patients). | Preprocessing pipeline (scaling, one-hot encoding, feature selection), GridSearchCV, Random Forest, Gradient Boosting, Logistic Regression, **SHAP** explainability | Random Forest: **87%** test accuracy |
| [**COVID-19 Patient Survival**](covid-19-analysis/) | Predicts patient survival on a large dataset of ~1M COVID-19 patient records. | Logistic Regression, Random Forest, Gradient Boosting | Gradient Boosting: **95%** accuracy |
| [**Titanic Survival Analysis**](titanic-survival-analysis/) | Analyzes how sex, class and family size affected survival. | Feature engineering (titles, family size), Logistic Regression, Random Forest | Random Forest: **83%** accuracy |

## Running the notebooks

Each notebook has an **Open in Colab** button at the top. The datasets are included in each project folder.

## Contact

[LinkedIn](https://linkedin.com/in/tamara-jovicic1)
