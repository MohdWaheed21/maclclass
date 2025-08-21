# 🛍️ Mall Customer Segmentation

A complete end-to-end **machine learning pipeline** that transforms **unlabeled mall customer data** into **meaningful business insights**.  
This project combines **unsupervised learning** for discovering customer groups with **supervised learning** for predicting future customers' segments.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0+-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📊 Project Overview

Customer segmentation helps businesses understand their audience and tailor marketing strategies.  
This project simulates how a retail **mall** might use **machine learning** to group its customers and predict which segment new customers belong to.

The workflow is as follows:

1. **Data Preprocessing**  
   - Clean raw customer data  
   - Encode categorical features (e.g., Gender)  
   - Scale features for clustering  

2. **Unsupervised Learning (K-Means)**  
   - Apply clustering to discover natural customer segments  
   - Use the **Elbow Method** to find the optimal number of clusters  

3. **Label Creation**  
   - Translate raw clusters into **meaningful business labels** such as:  
     - VIP Customers  
     - Spendthrifts  
     - Budget-Conscious  
     - Conservative Spenders  
     - Average Customers  

4. **Supervised Learning (Random Forest)**  
   - Train a predictive model using cluster labels as the target  
   - Evaluate accuracy, precision, recall, and F1-score  

5. **Business Insights**  
   - Enable **targeted marketing**  
   - Improve **inventory planning**  
   - Enhance **customer loyalty programs**  

---

## 🎯 Objectives

- Identify distinct customer segments based on demographics & spending behavior  
- Convert **unlabeled raw data → business-friendly labeled data**  
- Build a supervised model to predict customer segments  
- Deliver actionable insights for business decision-making  

---

## 📁 Dataset

The dataset used is the **Mall Customers Dataset** from Kaggle.  

**Features**:  
- `CustomerID` → Unique identifier (not useful for ML)  
- `Gender` → Male / Female  
- `Age` → Customer’s age  
- `Annual Income (k$)` → Annual income (in thousands)  
- `Spending Score (1-100)` → Score assigned by the mall  

**Source**: [Kaggle – Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  

---

## 🛠️ Installation

### Prerequisites
- Python 3.8+  
- `pip`  

### Install Dependencies
```bash
pip install -r requirements.txt
