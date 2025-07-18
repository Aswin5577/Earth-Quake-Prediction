# 🏚️ Earthquake Damage Prediction

This project predicts the severity of damage to buildings caused by earthquakes using machine learning. It was developed for a Kaggle classroom competition hosted by MDST and DrivenData.


## 🎯 Objective

The goal is to predict the **ordinal variable `damage_grade`**, which indicates how badly a building was affected:
- `1` → Low damage  
- `2` → Medium damage  
- `3` → Severe damage (almost complete destruction)

The dataset contains 39 features describing building structure, materials, geographic location, and usage.


## 📦 Project overview
Project Earth is an applied machine learning project developed in Jupyter Notebook form (project earth.ipynb). It demonstrates an end‑to‑end workflow: loading data, exploratory data analysis (EDA), feature engineering, model training/evaluation across multiple algorithms (e.g., scikit‑learn, XGBoost, statsmodels), and visualization (matplotlib, seaborn, plotly).


## Key Features
End‑to‑end ML workflow in a single, easy‑to‑run notebook.
Uses common Python data/ML stack: pandas, numpy, scikit-learn, xgboost, statsmodels, matplotlib, seaborn, and interactive plotly charts.
Clear cell sequencing: data load → clean → EDA → feature engineering → model training → evaluation → (optional) export.
Easily portable to scripts / package structure for production.
Ready for beginners to learn and for recruiters/interviewers to review.



## 🧠 Insights
- Adobe/mud and non-engineered RC structures are most vulnerable
- Engineered RC and zoning laws reduce damage risk
- Predictive modeling aids urban planning


## ⚠️ Challenges
- High-cardinality geo features → Frequency encoding
- Obfuscated categories → One-hot & CatBoost
- Class imbalance → Class weights
- Model interpretability → SHAP (offline)
