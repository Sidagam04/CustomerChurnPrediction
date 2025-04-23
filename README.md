# CustomerChurnPrediction
This project predicts whether a customer will discontinue a subscription-based service using machine learning techniques. It includes data preprocessing, feature engineering, model training, and performance evaluation with visualizations.

🧠 *Objective*
1.Predict the likelihood of a customer churning.
2.Analyze key factors that influence churn such as:Demographics (Age, Gender, Geography), Account information (Balance, Tenure, Credit Score, Products held), Activity level (IsActiveMember, etc.)
3.Provide business insights through model explainability (feature importance).

📁 *Dataset*
1.The dataset used is a .csv file inside a .zip archive.
2.It contains customer records with both numerical and categorical features.
3.Target variable: Exited (1 if customer left, 0 otherwise)

⚙️ *Technologies Used*
->Python
->Pandas, NumPy for data manipulation
->Matplotlib for visualizations
->Scikit-learn for machine learning models and metrics

📊 *Models Trained*
1. Random Forest Classifier
Robust, non-linear, ensemble-based
Evaluated with accuracy and ROC AUC
Feature importance plotted
2. Logistic Regression
Simple and interpretable linear model
ROC curve plotted for comparison

📈 *Evaluation*
1.ROC Curve comparison between Random Forest and Logistic Regression
2.AUC Score used to judge classification capability
3.Accuracy Score reported for both models



