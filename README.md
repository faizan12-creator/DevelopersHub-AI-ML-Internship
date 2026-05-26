# 🤖 DevelopersHub Corporation — AI/ML Engineering Internship

<div align="center">

![Python](https://img.shields.io/badge/Python-3.14-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-3.0.3-green?style=for-the-badge&logo=pandas)
![Scikit-learn](https://img.shields.io/badge/ScikitLearn-1.8.0-orange?style=for-the-badge&logo=scikit-learn)
![Gradio](https://img.shields.io/badge/Gradio-Latest-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**AI/ML Engineering Internship Tasks at DevelopersHub Corporation**

*4 out of 6 tasks completed | Due: 5th June 2026*

</div>

---

## 📋 Tasks Overview

| # | Task | Status | Tools Used |
|---|------|--------|-----------|
| 1 | Iris Dataset Visualization | ✅ Complete | Pandas, Seaborn, Matplotlib |
| 2 | Stock Price Prediction | ✅ Complete | yFinance, Scikit-learn |
| 3 | Heart Disease Prediction | ✅ Complete | Scikit-learn, Seaborn |
| 4 | Health Query Chatbot | ✅ Complete | Gradio, Requests |

---

## ✅ Task 1: Iris Dataset — Exploratory Data Analysis

### Objective
Load, inspect and visualize the Iris flower dataset to understand data trends and distributions.

### Dataset
- **Name:** Iris Dataset
- **Source:** Scikit-learn built-in
- **Size:** 150 samples, 4 features, 3 species

### Visualizations
| Chart | Purpose |
|-------|---------|
| 📊 Scatter Plot | Feature relationships between species |
| 📊 Histogram | Value distributions per feature |
| 📊 Box Plot | Outlier detection per species |

### Key Findings
- Setosa is clearly **separated** from other species
- **Petal Length and Petal Width** are the most important features
- Sepal width has the most outliers
- Dataset has **no missing values**

---

## ✅ Task 2: Stock Price Prediction

### Objective
Predict next day's closing price using historical stock data.

### Dataset
- **Stock:** Tesla Inc. (TSLA)
- **Source:** Yahoo Finance via yFinance
- **Period:** 2020 — 2024

### Models Used
| Model | MAE | R² Score |
|-------|-----|---------|
| Linear Regression | Low | High |
| Random Forest | Lower | Higher |

### Key Findings
- Random Forest performs **better** than Linear Regression
- Open, High, Low, Close, Volume are key features
- Historical data can predict next day price effectively

---

## ✅ Task 3: Heart Disease Prediction

### Objective
Predict whether a person is at risk of heart disease based on health data.

### Dataset
- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** Scikit-learn built-in
- **Size:** 569 samples, 30 features

### Models Used
| Model | Accuracy | AUC Score |
|-------|---------|----------|
| Logistic Regression | 97.37% | High |
| Decision Tree | 94.74% | Good |

### Key Findings
- Logistic Regression achieved **97.37% accuracy**
- Worst concave points and worst perimeter are top features
- No missing values in dataset

---

## ✅ Task 4: General Health Query Chatbot

### Objective
Build a chatbot that answers general health-related questions.

### Tools Used
- **Interface:** Gradio
- **Backend:** Python rule-based + HuggingFace API
- **Safety:** Harmful content filter implemented

### Features
- Answers health questions (fever, headache, diabetes, etc.)
- Safety filter for harmful queries
- Recommends doctor consultation
- Interactive web interface via Gradio

### Example Queries
- "What causes a sore throat?"
- "Is paracetamol safe for children?"
- "What are symptoms of diabetes?"

---

## 🛠️ Tech Stack

| Tool | Version | Usage |
|------|---------|-------|
| Python | 3.14 | Core language |
| Pandas | 3.0.3 | Data loading and analysis |
| NumPy | 2.4.6 | Numerical operations |
| Matplotlib | Latest | Base plotting |
| Seaborn | 0.13.2 | Advanced visualizations |
| Scikit-learn | 1.8.0 | ML models and datasets |
| yFinance | 1.4.0 | Stock market data |
| Gradio | Latest | Web interface |
| Jupyter Notebook | Latest | Interactive coding |

---

## 📁 Repository Structure

```
DevelopersHub-AI-ML-Internship/
├── Python intern/
│   ├── task1_iris.ipynb          ← Task 1 Notebook
│   ├── task2_stock.ipynb         ← Task 2 Notebook
│   ├── task3_heart.ipynb         ← Task 3 Notebook
│   ├── task4_chatbot.ipynb       ← Task 4 Notebook
│   ├── scatter_plot.png          ← Task 1 Chart
│   ├── histogram.png             ← Task 1 Chart
│   ├── boxplot.png               ← Task 1 Chart
│   ├── stock_prediction.png      ← Task 2 Chart
│   ├── heart_eda.png             ← Task 3 Chart
│   ├── heart_evaluation.png      ← Task 3 Chart
│   └── heart_features.png        ← Task 3 Chart
├── LICENSE
└── README.md
```

---

## 👨‍💻 About

- **Intern:** Faizan
- **Company:** DevelopersHub Corporation
- **Domain:** AI/ML Engineering
- **Due Date:** 5th June 2026

---

<div align="center">

Made with ❤️ during **DevelopersHub AI/ML Internship**

⭐ Star this repo if you found it helpful!

</div>
