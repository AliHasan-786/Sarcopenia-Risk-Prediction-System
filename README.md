# 🧠 Sarcopenia Risk Prediction System

This project evaluates multiple machine learning models to predict **sarcopenia**, a condition related to loss of muscle mass and strength. It demonstrates preprocessing pipelines, model comparison, and Tableau dashboarding.

## 📊 Overview

Three models were evaluated:

- **Logistic Regression**
- **Random Forest**
- **XGBoost**

Each model was evaluated using key metrics: **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **ROC AUC**.  
A final dashboard in **Tableau** was built to compare these metrics visually.

## 🛠 Technologies Used

- Python (pandas, scikit-learn, xgboost, seaborn, matplotlib)
- Tableau (for interactive model comparison)
- Pipelines (for preprocessing)
- ROC AUC & Feature Importance visualization

## 📁 File Structure

- `notebooks/MLFinal.ipynb`: Jupyter notebook with full code and model evaluation
- `assets/model_comparison_dashboard.png`: Screenshot of Tableau dashboard
- `requirements.txt`: Python dependencies
- `data/`: (Optional) Include a sample or dummy CSV for reference

## 📈 Sample Dashboard

![Model Comparison Dashboard](assets/model_comparison_dashboard.png)

## 📍 Key Results

| Model              | Accuracy | F1 Score | ROC AUC |
|-------------------|----------|----------|---------|
| Logistic Regression | ~0.81   | ~0.26    | --      |
| Random Forest       | ~0.86   | ~0.48    | --      |
| XGBoost             | ~0.85   | ~0.55    | --      |

> 🧠 **XGBoost** outperformed others in F1 Score and Recall, making it the best candidate for deployment.

## 📬 Contact

Ali Hasan  
[GitHub](https://github.com/AliHasan-786) | [LinkedIn](https://www.linkedin.com/in/alihasan786/)
