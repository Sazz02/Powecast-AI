# ⚡ PowerCast-AI

PowerCast-AI is a machine learning-powered web application to forecast electricity production and detect unusual patterns (anomalies) in the data.

Whether you're analyzing power trends or want to explore forecasting, this app gives you both visuals and predictions.

---

## 🔗 Live Web App

👉 Click here to try the app: [PowerCast-AI on Hugging Face](https://huggingface.co/spaces/Sazzz02/PowerCast)

---

## 🔍 Project Overview

- 📈 Predicts future electricity production using machine learning (XGBoost).
- 🧠 Detects **anomalies** in historical electricity data using Isolation Forest.
- 📊 Visualizes trends, patterns, and predictions.
- 🌐 Built with **Python, Pandas, Gradio, and Scikit-learn**.

---

## ✨ Features

- Real-time electricity forecasting
- Anomaly detection on time-series data
- User-friendly interface via Gradio
- Fully open-source

---

## 📦 Sample Inputs to Try

Use these values in the app:

| Lag_1 (Previous day) | Lag_2 (2 days ago) | Month | Year |
|----------------------|--------------------|-------|------|
| 90.1                 | 88.5               | 6     | 2022 |
| 92.3                 | 91.2               | 12    | 2023 |
| 95.0                 | 94.1               | 1     | 2024 |

> 📌 Note: The values are just examples based on past electricity production data.

---

## 💻 How to Run the Project Locally

1. **Clone the repository**

```bash
git clone https://github.com/Sazz02/Powecast-AI.git
cd Powecast-AI
