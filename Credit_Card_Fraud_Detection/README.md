 Credit Card Fraud Detection

Project Overview
This project focuses on detecting fraudulent credit card transactions using data-driven analysis and machine learning techniques.  
It demonstrates essential data analysis, data preprocessing, and model evaluation skills relevant to real-world financial datasets.

---

 Dataset
The dataset used is the **Credit Card Fraud Detection Dataset** from Kaggle:  
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

It contains:
- 284,807 transactions over two days in September 2013.
- Each transaction is labeled as **fraudulent (1) or non-fraudulent (0).
- Features are **numerically transformed (PCA components)** to maintain privacy.

---

Tools and Libraries
- Python
- Pandas, NumPy – Data manipulation and exploration  
- Matplotlib,Seaborn – Data visualization  
- Scikit-learn – Model training, scaling, and evaluation  
- Imbalanced-learn (SMOTE) – Handling imbalanced dataset

---

Data Preparation
1. Loaded the dataset and inspected its shape, data types, and missing values.  
2. Checked class imbalance - fraud cases are less than 0.2% of all transactions.  
3. Scaled numeric features using StandardScaler for uniformity.  
4. Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique).  

---

Exploratory Data Analysis (EDA)
- Explored the Transaction amounts distribution and fraudulent vs. non-fraudulent ratios.  
- Analyzed time-based patterns to see if fraud occured more during certain hours.  
- Visualized correlations among features and outlier transactions.  

Key Visualizations:
- Transaction Amount Distribution  
- Fraud vs. Non-Fraud Count  
- Correlation Heatmap  

---

Model Development
Trained several classification models to detect fraudulent transactions:

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|-----------|
| Logistic Regression | 99.2% | 93% | 86% | 89% |
| Decision Tree | 98.8% | 90% | 82% | 86% |
| Random Forest | 99.6% | 94% | 91% | 92% |

 The Random Forest Classifier achieved the best overall performance.

---

  Key Insights
| Insight | Description |
|----------|--------------|
| Imbalance Challenge | Fraud cases are extremely rare (<0.2%), requiring resampling. |
| Feature Importance | Certain PCA components strongly influence fraud detection. |
| Timing Factor | Fraud tends to occur more frequently during specific hours. |
| Model Strength | Random Forest outperforms simpler models in recall and F1 score. |

---

 Conclusion
- Fraud detection requires high recall to minimize missed frauds.  
- Resampling techniques (like SMOTE) are essential for fair model training.  
- Random Forest provides the best balance between precision and recall.  
- With proper optimization, such models can be integrated into real-time fraud monitoring systems.

---

 Future Analysis
- Implement real-time fraud detection pipelines using streaming data.  
- Apply Deep Learning (LSTM/Autoencoders)for anomaly detection.  
- Build an interactive dashboard (Streamlit or Power BI) for visual monitoring.

