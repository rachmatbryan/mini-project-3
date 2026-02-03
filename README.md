# Mini Project 3 – Customer Segmentation & Anomaly Detection

**Group:** 10  
**Team Members:** Aristide Kanamugire, Bryan Rachmat  

---

## 1. Problem Description (From Kaggle)

### Business Problem
Shopping malls collect large amounts of customer data through membership cards, but often lack clear insights into how different types of customers behave. The business problem addressed in this project is how to segment customers into meaningful groups based on demographic and spending behavior, and how to identify unusual customers who may represent either valuable VIPs or potential data issues. These insights can support targeted marketing strategies, personalized promotions, and improved customer engagement.

Unsupervised learning is appropriate because the dataset does not contain predefined labels or known customer segments. Instead of predicting an outcome, the goal is to discover patterns and structures within the data. Techniques such as clustering, dimensionality reduction, and anomaly detection is used to explore customer behavior.
---

## 2. Dataset Description

### Source and Size
- **Dataset:** Mall Customer Segmentation Dataset  
- **Source:** Kaggle  
- **Size:** 200 customers × 5 features  

### Features
- **CustomerID:** Unique identifier for each customer (removed before analysis)
- **Gender:** Customer gender (Male or Female)
- **Age:** Customer age
- **Annual Income (k$):** Estimated yearly income in thousands of dollars
- **Spending Score (1–100):** Score assigned by the mall based on purchasing behavior

### Preprocessing Steps
- Removed `CustomerID` as it has no analytical value.
- Encoded `Gender` numerically for algorithm compatibility.
- Standardized all numerical features using `StandardScaler` to ensure fair distance calculations in K-means.
- Fixed random seeds to ensure reproducibility.

---

## 3. Setup Instructions

### Install Dependencies
Create a virtual environment (optional) and install dependencies using:

```bash
pip install -r requirements.txt
```
---

## 4. Team Contributions

- Aristide: Data Processing and Analysis
- Bryan: Git,  Analysis


