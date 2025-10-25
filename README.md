# **Heart Attack Prediction – Model Comparison**

Data-Driven Risk Assessment for Early Cardiovascular Intervention

---

## **Overview**

**Heart Attack Prediction – Model Comparison** is a Python-based analytical study designed to estimate the probability of a patient experiencing a heart attack within the next five years. Using a public medical dataset (sourced from Kaggle), the project explores multiple statistical and machine learning models to identify the most reliable approach for early risk prediction.

This work highlights the importance of model evaluation, metric-based comparison, and responsible clinical inference in healthcare analytics.

---

## **Purpose of the Project**

Heart disease remains a leading global health challenge. Identifying at-risk individuals early can significantly improve treatment outcomes. This project supports that goal by testing multiple predictive models and comparing their performance to determine which provides the most reliable clinical insight.

### **Key Objectives**

🩺 **Predict Risk of Heart Attack**  
- Estimate the likelihood of a new patient being at risk within the next 5 years.

📊 **Model Comparison & Evaluation**  
- Train and compare multiple models to determine the best-performing predictor.

🎯 **Metric-Based Model Selection**  
- Evaluate models based on:
  - **Accuracy**
  - **Precision**
  - **True Positive Rate (Recall)**
  - **F1-Score**

---

## **Models Evaluated**

| Model | Purpose |
|------|---------|
| **Logistic Regression** | Baseline interpretable statistical model |
| **K-Nearest Neighbors (KNN)** | Distance-based classification approach |
| **Support Vector Machine (SVM)** | Maximizes class separation using optimal decision boundaries |

---

## **Workflow**

1. **Load and Inspect Dataset (Kaggle Source)**
2. **Data Cleaning & Preprocessing**
3. **Train-Test Split & Normalization**
4. **Model Training**
5. **Performance Evaluation (Precision, Accuracy, TPR, F1-Score)**
6. **Result Comparison & Conclusion**

---

## **Technologies & Skills**

| Skill / Tool | Description |
|-------------|-------------|
| **Python** | Main programming language |
| **Data Analysis** | Cleaning, feature understanding & preprocessing |
| **Machine Learning** | Model training and prediction |
| **Statistics** | Evaluation of model reliability using statistical metrics |
| **Jupyter Notebook** | Experiment execution and result visualization |

---

## **Getting Started**

Clone the repository and open the notebook:

```bash
git clone https://github.com/your-username/heart-attack-model-comparison.git
cd heart-attack-model-comparison
jupyter notebook HeartAttack_Model_Comparison.ipynb
