# loan-applicant-segmentation

# 🏦 Loan Applicant Segmentation & Financial Behavior Analysis

## 📌 Project Overview

Financial institutions often deal with customers having diverse borrowing behaviors and financial needs. Treating all applicants similarly can lead to inefficient lending strategies and poor customer targeting.

This project uses **Machine Learning (K-Means Clustering)** and **Financial Behavior Analysis** to identify distinct borrower segments and derive actionable business insights.

The goal is to understand customer borrowing patterns, classify applicants into meaningful groups, and provide recommendations for financial product targeting.

---

## 🎯 Objectives

* Analyze borrower demographics and financial behavior.
* Identify hidden customer segments using K-Means clustering.
* Visualize customer groups using PCA.
* Create borrower personas based on financial characteristics.
* Generate business recommendations for each customer segment.

---

## 📊 Dataset

The dataset contains information about loan applicants, including:

* Age
* Sex
* Job
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Loan Duration
* Purpose of Loan

Dataset Size:

* 1000 Loan Applicants
* Multiple demographic and financial attributes

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

Machine Learning Techniques:

* K-Means Clustering
* PCA (Principal Component Analysis)
* Feature Engineering
* Data Preprocessing
* Financial Behavior Analysis

---

## 📂 Project Workflow

### 1. Data Cleaning

* Removed unnecessary columns
* Handled missing values
* Standardized dataset

### 2. Exploratory Data Analysis

Analyzed:

* Age distribution
* Credit amount distribution
* Loan purposes
* Housing patterns
* Borrowing behavior trends

### 3. Feature Engineering

Created:

* Monthly Burden
* Age Groups
* Duration Groups

### 4. Data Preprocessing

* Label Encoding
* Standard Scaling

### 5. Customer Segmentation

Applied:

* K-Means Clustering
* Elbow Method
* Silhouette Analysis

### 6. PCA Visualization

Reduced multi-dimensional borrower data into a 2D space for cluster visualization.

### 7. Cluster Profiling

Generated borrower personas and business recommendations.

---

## 📈 Key Findings

### 🟦 Premium Borrowers

Characteristics:

* Highest loan amounts
* Short repayment periods
* Strong repayment capacity

Recommendation:

* Premium lending products
* Pre-approved loans
* Relationship banking services

---

### 🟩 Conservative Homeowners

Characteristics:

* Largest customer segment
* Stable borrowing behavior
* Home ownership dominance

Recommendation:

* Low-interest personal loans
* Insurance and wealth products

---

### 🟨 Long-Term Financing Customers

Characteristics:

* Large loans
* Long repayment durations
* Moderate monthly burden

Recommendation:

* Mortgage and long-term financing products

---

### 🟥 Emerging Borrowers

Characteristics:

* Youngest customer group
* Higher proportion of renters
* Small loan requirements

Recommendation:

* Credit-building programs
* Starter financial products

---

## 📊 Visualizations

### PCA Cluster Visualization

Demonstrates separation between borrower segments.

### Cluster Distribution

Shows population size of each borrower segment.

### Credit Amount by Cluster

Compares average loan sizes across customer groups.

### Monthly Burden Analysis

Highlights repayment patterns among borrower segments.

---

## 📷 Sample Results

Place screenshots inside the `/images` folder and update paths below:

```markdown
![PCA Visualization](images/pca_visualization.png)

![Cluster Distribution](images/cluster_distribution.png)

![Credit Amount by Cluster](images/credit_amount_cluster.png)
```

---

## 🚀 Future Improvements

* Streamlit Dashboard
* Real-time Borrower Profiling
* Credit Risk Prediction Model
* Recommendation Engine
* Interactive Business Intelligence Dashboard

---

## 👨‍💻 Author

Hrishikesh Choudhury
