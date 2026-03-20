# king-county-housing-ml-project
Machine learning project for housing price prediction (regression) and condition classification using Python, pandas, scikit-learn, Linear Regression, Logistic Regression, Random Forest, and GridSearchCV, with feature engineering, data preprocessing, cross-validation,  and model evaluation (RMSE, MAE, R², ROC-AUC).

- Built an end-to-end housing price prediction pipeline on King County data (20k+ records), using Linear Regression and Random Forest with cross-validated hyperparameter tuning (GridSearchCV).

Improved predictive performance over baseline linear model by implementing a tuned Random Forest (RMSE ↓, R² ↑), demonstrating gains from nonlinear modeling.
Engineered features (e.g., last_updated, categorical encodings) and removed redundant variables to improve model stability and interpretability.
Developed reproducible ML pipelines (ColumnTransformer + Pipeline) with imputation, scaling, and one-hot encoding; evaluated models on a held-out test set.
Produced model diagnostics and visualizations (predicted vs. actual, residuals, ROC/AUC, feature importance) to communicate key drivers of price.

