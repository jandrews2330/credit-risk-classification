# credit-risk-classification
# 💳 Credit Risk Analysis Report

## 📌 Overview of the Analysis

The purpose of this analysis is to evaluate whether a loan applicant poses a high credit risk. Using historical lending data, we built and tested a **logistic regression model** to predict loan status (healthy vs. high-risk). The model was trained on multiple financial features using supervised machine learning and assessed for accuracy and reliability.

This analysis aims to assist financial institutions in automating the risk assessment process for loan approvals, improving decision-making efficiency, and reducing exposure to default risk.

---

## 📊 Results

The performance of the **logistic regression model** is summarized below:

- ✅ **Accuracy Score**: **0.99** (99%)
- ✅ **Precision**:
  - **Class 0 (Healthy loan)**: **1.00**
  - **Class 1 (High-risk loan)**: **0.87**
- ✅ **Recall**:
  - **Class 0 (Healthy loan)**: **1.00**
  - **Class 1 (High-risk loan)**: **0.95**
- ✅ **F1-Score**:
  - **Class 0**: **1.00**
  - **Class 1**: **0.91**

---

## 🧠 Summary and Recommendation

The logistic regression model performs very well, achieving **99% overall accuracy**. It predicts healthy loans (`0`) with perfect precision and recall. For high-risk loans (`1`), it delivers a **recall of 95%**, correctly identifying nearly all risky applicants. Although the precision for high-risk loans is slightly lower (87%), the model still balances the trade-off effectively, with a strong **F1-score of 0.91**.

Given its high precision and recall, especially for high-risk borrowers, this model is **recommended for use** by the company. It can reliably support loan approval decisions by accurately flagging applicants who are likely to default, minimizing financial losses while maintaining approval efficiency.

---

**Tools Used:** Python, Pandas, scikit-learn, Jupyter Notebook  
**Acknowledgements:** Prepared using the provided dataset and starter notebook. Used prior class examples and the assistance of Xpert Learning Assistant. 