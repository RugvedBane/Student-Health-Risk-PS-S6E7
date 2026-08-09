# 🏥 Student Health Risk Prediction — Kaggle PS S6E7

![Kaggle](https://img.shields.io/badge/Kaggle-Playground%20Series%20S6E7-20BEFF?style=for-the-badge&logo=kaggle)
![Medal](https://img.shields.io/badge/Medal-🥉%20Bronze-cd7f32?style=for-the-badge)
![Score](https://img.shields.io/badge/Private%20LB-0.94975-brightgreen?style=for-the-badge)
![Rank](https://img.shields.io/badge/Rank-1382%20%2F%203356-blue?style=for-the-badge)

---

## 📌 Overview

This repository contains my solution for the **Kaggle Playground Series Season 6, Episode 7** competition — **Student Health Risk Prediction**.

The task was a multi-class classification problem: predicting the health risk level of students based on lifestyle, academic, and behavioral features.

---

## 🏆 Results

| Metric | Score |
|---|---|
| **Public Leaderboard** | 0.95014 |
| **Private Leaderboard** | 0.94975 |
| **Final Rank** | 1382 / 3356 |
| **Medal** | 🥉 Bronze |

> Note: Score dropped slightly on the private LB due to a leaderboard shake-up — a common occurrence in Kaggle competitions.

---

## 🧠 Approach

### 1. Exploratory Data Analysis
- Analyzed feature distributions, class imbalance, and correlations
- Identified key lifestyle and academic features influencing health risk
- Visualized patterns across health risk categories

### 2. Feature Engineering
- Created custom interaction features that captured hidden relationships in the data
- These engineered features received notable community attention in the comments

### 3. Modelling
- Primary model: **LightGBM**
- Hyperparameter tuning with **Optuna** (automated search over 50+ trials)
- Compared multiple models to find the best performer

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python)
![LightGBM](https://img.shields.io/badge/LightGBM-Model-brightgreen?style=flat)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter%20Tuning-blue?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=flat&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Preprocessing%20%26%20Metrics-F7931E?style=flat&logo=scikit-learn)

---

## 📂 Repository Structure

```
Student-Health-Risk-PS-S6E7/
├── notebooks/
│   ├── Eda.ipynb       # Exploratory Data Analysis
│   └── Model.ipynb     # Feature Engineering + LightGBM + Optuna
└── README.md
```

---

## 📓 Kaggle Notebooks

| Notebook | Upvotes | Medal |
|---|---|---|
| [🔬 Modeling — LightGBM + Optuna \| 0.95014](https://www.kaggle.com/code/rugvedbane/student-health-risk-lightgbm-optuna-0-95014) | 38 ⬆️ | 🥉 Bronze |
| [📊 Beginner-Friendly EDA \| PS S6 E7](https://www.kaggle.com/code/rugvedbane/beginner-friendly-eda-ps-s6-e7) | 5 ⬆️ | — |

---

## 👤 Author

**Rugved Bane**

[![Kaggle](https://img.shields.io/badge/Kaggle-rugvedbane-20BEFF?style=flat&logo=kaggle)](https://www.kaggle.com/rugvedbane)
[![GitHub](https://img.shields.io/badge/GitHub-RugvedBane-181717?style=flat&logo=github)](https://github.com/RugvedBane)
