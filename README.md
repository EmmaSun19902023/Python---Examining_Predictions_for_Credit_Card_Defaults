# Examining_Predictions_for_Credit_Card_Defaults_Project
Developing Machine Learning models and Examining Predictions based on American Express's credit card default dataset.

Created a function which utilizes StratifiedKFold with 4 folds, a pipeline incorporating preprocessor and machine learning algorithm, GridSearchCV for hyperparameter tuning and the F-beta score evaluation metric. This function facilitates the exploration of various algorithms, including Logistic Regression, Decision Tree, Random Forest and XGBoost.

The process involves iterating through 10 different random states. After preprocessing, the function fits the model and then calculates the F-beta test score for each iteration, ultimately returning lists containing 10 test scores and the corresponding 10 best models.

Decision Tree stands out as the best performer based on the combination of metrics. It achieved a mean test score of 94.01%, indicating a high level of accuracy. Additionally, the model demonstrated a relatively low standard deviation of 0.0030, resulting in a Coefficient of Variation of 0.0032. The Number of Std Above Baseline value of 279.63 further emphasizes the model's superiority, surpassing the baseline accuracy by nearly seven standard deviations. 

Required library versions:

python=3.10.5

matplotlib=3.5.2

pandas=1.4.2

scikit-learn=1.1.1

numpy=1.22.4

xgboost=1.5.1

shap=0.40.0

jupyter_client=7.3.1

jupyter_core=4.10.0

jupyterlab=3.4.2

jupyter_server=1.17.0

jupytext=1.13.8

rise=5.7.1

plotly=5.8.0

ipywidgets=7.7.0
