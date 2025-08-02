🩺 Healthcare Data Analysis & Regression Modeling
This project focuses on understanding and predicting healthcare-related outcomes through structured data analysis and machine learning modeling. The steps involved span from exploratory data analysis to building interpretable regression models using both linear and non-linear approaches.

📊 1. Exploratory Data Analysis (EDA)
Univariate Analysis:
Examined the distribution of each variable individually using histograms, box plots, and density plots to understand the spread, skewness, and presence of outliers.

Bivariate Analysis:
Analyzed relationships between key features and the target variable using scatter plots, correlation matrices, and grouped box plots to identify potential predictors.

Insights Drawn:
Identified feature-target dependencies, multicollinearity, and data imbalance issues that informed later modeling steps.

🧹 2. Data Preprocessing & Feature Engineering
Data Cleaning:
Handled missing values, outliers, and inconsistent entries to prepare a robust dataset for modeling.

Encoding & Transformation:

Categorical features were one-hot or label encoded depending on their nature.

Continuous features were scaled for consistency across models.

Feature Engineering:

Created derived variables where needed (e.g., ratios, binning).

Selected important features based on domain knowledge and statistical relevance.

🧪 3. Model Preparation
Train-Test Split:
The dataset was divided into training and test sets to evaluate generalization performance. A standard 80/20 split was used, with cross-validation applied during training.

🤖 4. Model Building: Linear & Non-Linear Regression
A variety of regression models were implemented and compared:

🔷 Linear Models:
Linear Regression:
Simple and interpretable baseline model.

Ridge Regression:
Used to reduce overfitting by penalizing large coefficients (L2 regularization).

🔶 Non-Linear Models:
Decision Tree Regressor:
Captures non-linear interactions between features.

Bagging Regressor:
Aggregates multiple models to reduce variance.

Random Forest Regressor:
An ensemble of decision trees offering robustness and better performance.

Tuned Random Forest (Grid Search):
Hyperparameter tuning was performed to optimize the random forest using GridSearchCV for the best combination of parameters.

📏 5. Model Evaluation Metrics
Each model was assessed using the following metrics:

Root Mean Squared Error (RMSE) – Penalizes large errors more than MAE.

Mean Absolute Error (MAE) – Measures average magnitude of errors.

R-Squared (R²) – Represents the proportion of variance explained by the model.

All models were compared using these metrics to identify the best-performing algorithm.

✅ 6. Final Model Selection & Prediction
Based on evaluation metrics, the best-performing model was selected.

This model was then used to generate predictions on the test data.

Performance was visualized using residual plots and actual vs predicted plots to validate assumptions.

📌 7. Model Interpretability with SHAP
SHAP (SHapley Additive exPlanations) was used to interpret how each feature contributes to individual predictions.

Plotted SHAP summary and dependence plots to:

Identify the most influential features.

Explain the direction and magnitude of feature impacts on predictions.

Helped improve transparency and trust in the model’s decision-making.

📁 Project Highlights
Comprehensive EDA to build intuition about the dataset.

A full pipeline from preprocessing to advanced ensemble modeling.

Interpretable model outputs using SHAP values.

A clear comparison between linear and non-linear regression models.



