# jpmorgan-quantitative-research-simulation
Quantitative Research simulation covering commodity pricing, credit risk modeling, and FICO score bucketing using Python
# JPMorgan Quantitative Research Virtual Experience (Forage)

## 📌 Overview

This project is based on the JPMorgan Chase Quantitative Research Job Simulation hosted on Forage. The objective was to solve real-world problems faced by quantitative analysts in areas such as commodity pricing, risk modeling, and credit analytics.

The project is divided into four key tasks, each focusing on a different aspect of quantitative finance and data analysis.

---

## 🧠 Key Objectives

* Analyze financial time-series data
* Build pricing models for commodity contracts
* Develop credit risk prediction models
* Transform continuous financial variables into categorical features

---

## 📊 Tasks and Implementation

### **Task 1: Natural Gas Price Analysis**

* Processed historical monthly gas price data
* Interpolated data to estimate prices for any given date
* Modeled seasonality and trend to forecast future prices
* Built a function to return gas price for any input date

---

### **Task 2: Commodity Storage Contract Pricing**

* Developed a pricing model for gas storage contracts
* Considered:

  * Injection and withdrawal dates
  * Storage costs
  * Transport and operational costs
* Computed total profit/loss based on trading strategy

---

### **Task 3: Credit Risk Analysis (PD & Expected Loss)**

* Built a predictive model to estimate Probability of Default (PD)

* Used Decision Tree Classifier for stability on small datasets

* Calculated Expected Loss using:

  ```
  Expected Loss = PD × LGD × Exposure
  ```

  where:

  * LGD (Loss Given Default) = 90% (assuming 10% recovery rate)

* Removed non-informative features (e.g., customer_id) to avoid overfitting

---

### **Task 4: FICO Score Bucketing (Quantization)**

* Converted continuous FICO scores into categorical ratings
* Used quantile-based bucketing for balanced distribution
* Created a mapping function for future data
* Ensured:

  * Higher FICO → Lower risk rating
  * Lower FICO → Higher risk rating

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 📈 Key Learnings

* Handling real-world financial datasets
* Importance of data preprocessing and feature selection
* Building interpretable models for risk estimation
* Understanding trade-offs between model simplicity and accuracy
* Translating business problems into quantitative solutions

---

## 📎 Certification

This project was completed as part of the JPMorgan Quantitative Research Virtual Experience Program.

📄 Certificate:

---

## 🚀 Conclusion

This project demonstrates the application of quantitative methods in finance, including pricing, forecasting, and risk modeling. It highlights the importance of combining domain knowledge with data-driven techniques to solve practical financial problems.

---
