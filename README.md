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

## 📁 Repository Structure

```text
Gender-Bias-in-Recommendation-Systems/
├── .gitignore               # Ignored files and virtual environments
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
├── data/
│   └── ml-100k/             # MovieLens 100K Benchmark Dataset
│       ├── u.data           # User interaction logs (ratings)
│       ├── u.item           # Movie metadata (genres, titles)
│       └── u.user           # User demographics (age, gender, occupation)
└── src/
    └── final.ipynb          # End-to-end analysis, training, and evaluation notebook
