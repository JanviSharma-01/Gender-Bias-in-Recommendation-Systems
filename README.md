# 🎯 Gender Bias in Recommendation Systems

An end-to-end Machine Learning project that analyzes and mitigates demographic gender bias in collaborative filtering and recommendation algorithms using the MovieLens 100K benchmark dataset.

---

## 📌 Executive Summary

Recommender systems heavily influence user decisions on modern digital platforms. However, when trained on historical user interaction data, these models often learn, amplify, and perpetuate demographic biases. 

This project explores:
* 🔍 **Bias Identification:** How gender bias manifests in recommendation predictions on the MovieLens 100K dataset.
* 📊 **Quantitative Metrics:** Measuring disparities in prediction accuracy and recommendation fairness across demographic groups.
* 🛠️ **Algorithmic Mitigation:** Applying debiasing techniques to reduce demographic disparity while minimizing trade-offs in overall predictive accuracy (RMSE/MAE).

---
## 🏗️ System Architecture & Workflow

```text
┌─────────────────────────────────────────────────────────┐
│                    MovieLens 100K                       │
│      (User Interactions, Movie Metadata, Demographics)  │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│              Exploratory Data Analysis                  │
│       • Demographic Distributions & Interaction Patterns│
│       • Rating Disparities & Preference Variance        │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│              Collaborative Filtering Models             │
│       • User / Item KNN & Matrix Factorization (SVD)    │
│       • Group-Level Performance Disparity (RMSE/MAE)    │
└───────────────────────────┬─────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│          Bias Evaluation & Mitigation Engine            │
│       • Fairness Metrics (FairNDCG, Disparate Impact)   │
│       • Debiasing (Pre/In/Post-processing)              │
└─────────────────────────────────────────────────────────┘

