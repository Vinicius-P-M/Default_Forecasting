# Predicting Sovereign Defaults: A Comparative Approach Using Logistic Regression and KNN  

**Author:** Vinicius Paulinelli  
**Date:** 2025  

## 📘 Overview  

This project compares the performance of **Logistic Regression** and **K-Nearest Neighbors (KNN)** models in forecasting **sovereign defaults** — situations where a country fails to repay its contracted debt.  

The analysis uses economic indicators from the **IMF** and **World Bank**, focusing on their predictive value for credit risk at the sovereign level. It illustrates the practical challenges of applying supervised learning to macro-financial phenomena, where political and structural factors often play a key role.  

---

## 📊 Data and Variables  

The dataset combines IMF and World Bank statistics with a binary default indicator. Independent variables include:  

- **Current account balance (% of GDP)**  
- **Total reserves (% of foreign debt)**  
- **Total government debt (% of GDP)**  

The target variable (`default_dummy`) equals **1** if a country defaulted in a given year, and **0** otherwise.  

All transformations and variable classifications were performed using the `default_dummy.xlsx` file. The most balanced distribution of defaults and non-defaults was observed in **2019**, which became the reference year for model evaluation.  

---

## ⚙️ Methodology  

1. **Data Preprocessing:** Cleaning, scaling, and transforming macroeconomic indicators.  
2. **Model Training:**  
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
3. **Evaluation:**  
   - Accuracy  
   - Precision  
   - Recall  
   - Confusion Matrix and ROC analysis  

---

## 📈 Results and Interpretation  

Both models exhibited **low predictive performance**, highlighting the limitations of using purely quantitative macroeconomic variables to anticipate sovereign defaults.  

This outcome suggests that **non-economic factors** — such as political risk, institutional quality, and regime stability — play a decisive role in sovereign credit events and should be included in future iterations.  

---

## 🧰 Tools and Libraries  

- **Python**  
- **NumPy**  
- **pandas**  
- **scikit-learn**  
- **seaborn**  

**Additional file:** `default_dummy.xlsx` — contains binary default classifications and supporting data.  

---

## 💡 Key Takeaway  

Predicting sovereign defaults is not only a statistical challenge but a political one. This project demonstrates how traditional machine learning models handle macro-financial prediction tasks — and where their limits begin.  
