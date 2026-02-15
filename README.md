# Predictive-analysis-in-sports

# 🔵🔴 FC Barcelona: The Chaos Factor & Possession Paradox
An Advanced Data Science project exploring the relationship between control, efficiency, and match outcomes.

## 📊 Project Overview
This project analyzes 120+ matches (2023-2025) to determine what actually drives a victory for FC Barcelona. We move beyond basic statistics to build a **Random Forest Classifier** that predicts match outcomes with a focus on "Clinical Efficiency."

## 🚀 Key Insights
* **The Possession Paradox:** While Barca averages 63% possession, the correlation with goals scored is surprisingly weak (0.16).
* **The UCL Boost:** Barcelona exhibits a "European Chaos Factor," being 6x more clinical in the Champions League compared to La Liga.
* **Predictive DNA:** Our Machine Learning model identified **Pass Accuracy** and **Expected Goals (xG)** as the most reliable predictors of a win.

## 🤖 Machine Learning Model
We utilized a **Random Forest Classifier** optimized via `GridSearchCV`. 
* **Accuracy:** 64% (Optimized)
* **Features:** Possession, xG, Shots on Target, Pass Accuracy, and Efficiency Gap.

## 🛠️ Tech Stack
* **Python** (Pandas, NumPy)
* **Scikit-Learn** (Random Forest, GridSearchCV)
* **Visualization** (Seaborn, Matplotlib)
