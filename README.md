# 💸 Fintech Financial Analysis and Bankruptcy Prediction

## 🧾 Problem Statement

A fintech firm preparing to pivot to an AI-first strategy has entrusted the analysis of its financial data to guide this transition. The firm seeks to unlock key operational efficiencies and mitigate financial risks—particularly bankruptcy—by leveraging predictive and descriptive analytics.

---

## 🎯 Objective

- Analyze company financial data to identify patterns of financial distress.
- Apply machine learning techniques (classification, clustering, regression) for business strategy development.
- Predict company bankruptcy and segment firms based on financial health.
- Build a data-driven foundation for the firm’s AI-enabled future.

---

## 📂 Dataset Description

The dataset contains anonymized financial metrics of various companies, including:

- **Financial Ratios**: such as ROA, debt ratio, net profit margin, equity-to-asset ratio.
- **Target Variable**: `Bankrupt?` (0 or 1)
- **Time Series Indexing**: to analyze trends over time.
- **Derived Indicators**: cash flow ratios, Z-score metrics, financial leverage, etc.

---

## 🔍 Tasks Performed

1. **Data Preprocessing**
   - Handled missing values and outliers.
   - Scaled and normalized financial indicators.
   - Applied feature selection techniques to reduce dimensionality.

2. **Bankruptcy Prediction**
   - Built classification models (Logistic Regression, Random Forest, XGBoost) to predict bankruptcy.
   - Evaluated models using accuracy, ROC-AUC, precision, and recall.

3. **Clustering for Financial Segmentation**
   - Applied K-Means and Hierarchical Clustering to categorize companies into financial health groups.
   - Visualized clusters using PCA and t-SNE.

4. **Exploratory Data Analysis**
   - Analyzed key indicators contributing to financial distress.
   - Time series and distribution plots to reveal business cycles and anomalies.

---

## 🛠️ Tools and Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Modeling and evaluation
- **XGBoost** – Advanced classification
- **t-SNE / PCA** – Dimensionality reduction for visualization

---

## 📈 Key Metrics Evaluated

- **Accuracy** and **ROC-AUC** for classification.
- **Silhouette Score** for clustering.
- **Confusion Matrix** and **Classification Report**.
- **Correlation Heatmaps** for feature importance analysis.

---

## 💡 Business Insights

- Companies with low profitability, negative cash flows, and high leverage showed higher bankruptcy risk.
- Clustering helped identify ‘at-risk’, ‘stable’, and ‘growing’ companies.
- Predictive modeling provided a foundation for early warning systems.

---

## 🚀 Future Scope

- Integrate financial forecasting using LSTM or ARIMA models.
- Build an end-to-end automated monitoring dashboard using Streamlit or Power BI.
- Extend analysis to include macroeconomic indicators and external financial news for context-based predictions.

---
