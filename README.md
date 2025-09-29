# insulin_release_period

Insulin Period Prediction
This project explores how food composition and glycemic index (GI) influence insulin release periods, with the goal of developing predictive models that can support personalized glucose management. Using machine learning, the project evaluates the relative impact of macronutrients and GI on insulin dynamics.
Project Overview
Objective: Predict insulin release periods within a 2-hour window based on nutritional features.
Dataset: Nutritional composition (proteins, lipids, carbohydrates, fiber, glycemic index) derived from food equivalence tables.
Models Tested:
Baseline: Linear Regression
Ensemble methods: Random Forest, LightGBM (with Optuna hyperparameter tuning)
Evaluation Metrics: RMSE, R², MAPE
Interpretability: SHAP values used to identify and visualize feature contributions.
Key Findings
The glycemic index (GI) was the strongest predictor of insulin release.
Macronutrients (especially carbohydrates and fiber) contributed significantly to predictions.
Ensemble models (Random Forest, LightGBM) consistently outperformed linear models in accuracy and robustness.
Tools & Libraries
Python, pandas, numpy
scikit-learn, LightGBM, Optuna
Matplotlib, Seaborn, SHAP
Potential Applications
Informing personalized nutrition strategies for individuals managing glucose levels.
Providing a data-driven foundation for medical device integration (e.g., insulin pumps, CGM systems).
Supporting clinical research on the interplay between diet and insulin dynamics.