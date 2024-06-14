# Python: Examining_Predictions_for_Credit_Card_Defaults
Developing machine learning models and examining predictions based on American Express's credit card default dataset.

A function is created to combine all the steps, including a pipeline containing preprocessor and machine learning algorithms, GridSearchCV for hyperparameter tuning and F-beta score as evaluation metric. This function facilitates exploring various algorithms such as logistic regression, decision tree and random forest. 

In loops through ten random states, the model is fitted after preprocessing and splitting, and then the F-beta test score is calculated. At the end of iterations, the function returns a list of ten test scores along with ten best models for each algorithm.

Decision Tree stands out as the best in performance based on the combination of metrics. It achieved a mean of test score value of 94.01%, indicating a strong ability to balance precision and recall. Additionally, the model demonstrated a relatively low standard deviation of test score value of 0.0030, resulting in a coefficient of variation of test score value of 0.0032. The number of standard deviation above baseline value of 279.63 further emphasizes the model's superiority, surpassing the baseline accuracy by nearly 280 standard deviations. 

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
