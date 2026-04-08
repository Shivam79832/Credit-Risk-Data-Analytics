# 🏦 Credit Risk Data Analytics 

> **Project Hook:** I help financial institutions save money by identifying high-risk borrowers using advanced data cleaning and statistical correlation.

---

## 📊 Business Executive Summary
In this project, I analyzed a dataset of 32,000+ loan applications. By cleaning "noisy" data and analyzing financial variables, I discovered the key thresholds where a borrower is most likely to default.

### Key Finding:
**Loan-to-Income Ratio** is the strongest predictor of default. Borrowers spending over **22% of their monthly income** on loan repayments show a significantly higher probability of default.

---

## 🛠️ Technical Implementation (Skills Used)

### 1. Data Cleaning & Integrity (Python/Pandas)
* **Outlier Removal:** Identified and removed impossible data points (e.g., Age > 100, Employment > 60 years).
* **Missing Value Imputation:** Handled 3,000+ null values in interest rates using **Median Imputation** to prevent data bias.

### 2. Exploratory Data Analysis (EDA)
* **Correlation Analysis:** Used Pearson Correlation to find the relationship between loan status and financial metrics.
* **Technology:** Used `df.corr()` to identify high-risk variables.

### 3. Visual Storytelling (Seaborn/Matplotlib)
* Created **Heatmaps** and **Box Plots** to visualize the distribution of debt across "Safe" vs "Default" categories.

---

## 🎯 Final Business Recommendation
Based on the data, the bank should implement a **"High-Risk Flag"** for any borrower whose loan amount exceeds **22% of their annual income**, as this group accounts for the majority of defaults.
