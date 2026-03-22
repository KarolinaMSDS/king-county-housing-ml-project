# king-county-housing-ml-project

# 🏠 King County Housing Price Prediction

**Machine Learning | Regression & Classification | scikit-learn**

Machine learning project for housing price prediction (regression) and condition classification using Python, pandas, scikit-learn, Linear Regression, Logistic Regression, Random Forest, and GridSearchCV, with feature engineering, data preprocessing, cross-validation,  and model evaluation (RMSE, MAE, R², ROC-AUC).

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Libraries](https://img.shields.io/badge/Libraries-pandas%20%7C%20scikit--learn-orange)
![Data](https://img.shields.io/badge/Data-Structured%20Tabular-green)
![Models](https://img.shields.io/badge/Models-Linear%20Regression%20%7C%20Random%20Forest-purple)
![Task](https://img.shields.io/badge/Task-Regression%20%7C%20Classification-lightgrey)
![Best Model](https://img.shields.io/badge/Best-Tuned%20Random%20Forest-brightgreen)

## Impact & Applications

This project shows how machine learning can be used to predict housing prices using real-world data. The tuned Random Forest model outperformed linear regression, indicating that nonlinear relationships and feature interactions are important in housing price prediction. **Feature importance analysis showed that living area, construction quality (grade), location, and waterfront access were the strongest drivers of price. These results illustrate how data-driven models can support pricing decisions, property valuation, and real estate investment analysis.**

---

## 📊 Dataset

* ~20,000 housing records
* Features include:

  * Living area (sqft)
  * Construction grade
  * Location (latitude/longitude)
  * Waterfront access
  * Property and neighborhood characteristics

---

## 🧠 Models Implemented

### 1. Linear Regression

* Baseline, highly interpretable model
* Limited ability to capture nonlinear relationships

---

### 2. Random Forest

* Captures nonlinear relationships and feature interactions
* Improved performance over linear regression

---

### 3. Tuned Random Forest ⭐ (Best Model)

* Hyperparameter tuning using GridSearchCV
* Best overall predictive performance

### 4. Logistic Regression  
- Baseline classification model  
- Interpretable coefficients  
- Evaluated with ROC-AUC  

---

## 📈 Results

| Model               | Key Outcome                                    |
| ------------------- | ---------------------------------------------- |
| Linear Regression   | Strong baseline, interpretable                 |
| Random Forest       | Improved performance, captures complexity      |
| Tuned Random Forest | **Best performance (lowest RMSE, highest R²)** |

<p align="left">
  <img src="model_comparison_table.png" width="80%">
</p>

---

## 🔍 Key Findings

* The **tuned Random Forest model outperformed linear regression**, demonstrating the importance of nonlinear modeling.
* Feature importance analysis identified **sqft_living, grade, location, and waterfront access** as the strongest predictors of price.
* Machine learning models can effectively support **property valuation, pricing strategies, and real estate investment decisions**.

---

## 📊 Model Interpretation

### Predicted vs Actual Prices

<p align="left">
  <img src="predicted_vs_actual.png" width="50%">
</p>

The tuned Random Forest model closely tracks actual housing prices, indicating strong predictive accuracy.

---

### 🧾 Feature Importance

<p align="left">
  <img src="feature_importance.png" width="60%">
</p>

Key drivers of housing prices include:

* **sqft_living** — primary determinant of value
* **grade** — construction quality significantly impacts price
* **location (lat/long)** — geographic variation drives market differences
* **waterfront access** — premium feature
* **neighboring property characteristics** — local context matters

---

## ⚙️ Modeling Approach

* Built an end-to-end machine learning pipeline using **pandas and scikit-learn**
* Applied **data preprocessing** (imputation, scaling, encoding) using `ColumnTransformer`
* Used **GridSearchCV** for hyperparameter tuning
* Evaluated models using **RMSE, MAE, R², and ROC-AUC (for classification)**
* Generated visual diagnostics (predicted vs actual, residuals, ROC/AUC, feature importance)

---

## ⚠️ Limitations

* Dataset represents a **single year of housing sales**
* Missing potentially important features (e.g., school districts, amenities)

---

## 🚀 Key Takeaway

This project demonstrates that **tree-based ensemble models like Random Forest significantly outperform linear models** for complex, real-world prediction tasks by capturing nonlinear relationships and feature interactions.

---


