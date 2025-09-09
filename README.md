## Cyber Security Detection Using XAI

This project demonstrates how Explainable Artificial Intelligence (XAI) can be applied to cybersecurity threat detection. Traditional ML models can identify threats but often work like a black box. By integrating XAI methods such as SHAP, LIME, and feature importance, this project provides both high accuracy in detecting threats and interpretability, helping security analysts understand why a model flagged a threat.

#Features

📊 Threat Detection using ML classifiers.

🔍 Explainability with XAI – SHAP, LIME, and feature importance visualizations.

⚡ Efficient Preprocessing – handles categorical, numerical, and imbalanced data.

📈 Model Evaluation – accuracy, precision, recall, F1-score, ROC curves.

🎨 Visual Explanations – feature impact and per-sample explanations.

🔒 Cybersecurity-focused – phishing and network threat datasets.

#Tech Stack

Language: Python 🐍
Libraries:
pandas, numpy → data preprocessing
scikit-learn → ML models & metrics
xgboost → gradient boosting classifier
matplotlib, seaborn → visualizations
shap → explainability
Environment: Jupyter Notebook

#Results

Achieved high classification accuracy across datasets using ensemble models.

Random Forest / XGBoost performed best in detection.

XAI visualizations showed that:

For phishing, URL-based features (e.g., length, presence of @, redirects) were most important.

For network threats, protocol type and connection duration were key indicators.

Final output included interpretable dashboards of feature contributions.
