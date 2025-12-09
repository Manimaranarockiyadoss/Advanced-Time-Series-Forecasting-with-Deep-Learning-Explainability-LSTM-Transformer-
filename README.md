🧠 Advanced Time Series Forecasting with Deep Learning & Explainability
(LSTM + Transformer + SHAP)






📌 Overview

This project performs multivariate time-series forecasting using

LSTM

Transformer

and Explainability (SHAP)

Performance is compared against classical baselines such as Naive and Exponential Smoothing.

The goal is to demonstrate:

deep learning forecasting

hyperparameter tuning

time-series evaluation metrics

post-hoc explainability

🔥 Main Features

✔ Advanced LSTM architecture
✔ Transformer Encoder block
✔ Time windowing & scaling
✔ Baseline comparison
✔ Multiple error metrics
✔ SHAP explainability
✔ Fully reproducible

🧮 Evaluation Metrics

RMSE

MAE

MAPE

MASE (required for evaluation)

📊 Architecture Used
LSTM Model

stacked LSTMs

dropout regularization

linear output

Transformer Model

multi-head attention

positional encoding

feed-forward network

🗂 Repository Structure
.
├── data/
│   └── dataset.csv
├── scripts/
│   └── main.py
├── model_comparison_results.csv
├── requirements.txt
└── README.md

🚀 Getting Started
1️⃣ Clone
git clone https://github.com/YOURNAME/forecasting-project.git
cd forecasting-project

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run project
python scripts/main.py

🧠 Explainability (SHAP)

This project uses SHAP DeepExplainer to analyze:

feature importance

time-step importance

lag influence

This enables full interpretability of deep-learning models.

📈 Example Result Visualizations

Prediction vs Ground Truth

SHAP feature importance

Attention insight

Comparative metrics table

📎 Results Summary (Example)
Model	RMSE	MAE	MAPE	MASE
Naive				
ExpSmooth				
LSTM				
Transformer				

Transformer generally performs best across metrics.

🛠 Requirements
numpy
pandas
matplotlib
scikit-learn
tensorflow
statsmodels
shap
