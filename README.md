
# 🌍 Earthquake Prediction — SVM + GBM
### ML · Geoscience | Seismic Event Classification

> Ensemble machine learning approach for earthquake occurrence classification using Support Vector Machines and Gradient Boosting on historical geological datasets. Achieves **68% accuracy** on seismic event prediction.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![SVM](https://img.shields.io/badge/Model-SVM%20%2B%20GBM-teal?style=flat-square)
![Accuracy](https://img.shields.io/badge/Accuracy-68%25-gold?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-Geoscience%20%7C%20Seismology-brown?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)

> 🔒 **Private Repo · README only.** Source code not publicly accessible.

---

## 📌 Overview

Earthquake prediction is one of the most challenging problems in geoscience — seismic events are rare, complex, and governed by non-linear geological dynamics. This project applies an **ensemble of Support Vector Machine (SVM) and Gradient Boosting Machine (GBM)** classifiers to historical seismic datasets to predict earthquake occurrence with **68% classification accuracy**.

The project draws directly on domain knowledge from a background in seismology, combining geoscientific understanding with modern ML methodology.

---

## 🎯 Objective

Classify whether a seismic event of significant magnitude will occur based on historical geological and seismic features — including fault activity, depth, prior event frequency, and regional stress indicators.

---

## 🧱 Technical Approach

| Component | Detail |
|---|---|
| **Dataset** | Historical geological and seismic event records |
| **Feature Engineering** | Fault proximity, depth, inter-event timing, magnitude history, regional stress indicators |
| **Models** | Support Vector Machine (RBF kernel), Gradient Boosting Machine |
| **Ensemble Strategy** | Soft voting / stacking of SVM and GBM predictions |
| **Evaluation** | Accuracy, Precision, Recall, F1, Confusion Matrix |
| **Accuracy** | **68%** on earthquake occurrence classification |

---

## 🔬 Methodology

1. **Data Preprocessing** — cleaning historical seismic records, handling class imbalance (earthquake events are rare), feature normalisation
2. **Feature Engineering** — derived geoscientific features including inter-event intervals, depth-magnitude interaction terms, and fault zone proximity scores
3. **SVM Classifier** — RBF kernel SVM trained on normalised feature vectors; effective for high-dimensional, non-linear seismic decision boundaries
4. **GBM Classifier** — Gradient Boosting trained on the same feature set; captures complex non-linear interactions between geological variables
5. **Ensemble** — combined SVM and GBM predictions via soft voting to improve robustness over either model individually
6. **Evaluation** — tested on holdout set with focus on recall for positive (earthquake) class given the cost of false negatives

---

## 📊 Results

| Metric | Score |
|---|---|
| Classification Accuracy | **68%** |
| Task | Binary earthquake occurrence classification |
| Baseline | Significantly above random / frequency baseline |

---

## 🔑 Key Takeaways

- Ensemble of SVM + GBM outperforms either model individually on seismic classification
- Geoscience domain knowledge critical for meaningful feature engineering
- Class imbalance handling essential — earthquake events are rare in historical data
- 68% accuracy represents a strong result given the inherent unpredictability of seismic systems

---

## 🛠️ Tech Stack

`Python` `scikit-learn` `XGBoost` `Pandas` `NumPy` `Matplotlib` `Seaborn`

---

## 👩‍💻 Author

**Arpita Paul** · Senior Data Scientist · *From Seismology to GenAI 🚀*

[![GitHub](https://img.shields.io/badge/GitHub-ArpitaAI--collab-black?style=flat-square&logo=github)](https://github.com/ArpitaAI-collab)
