# Transaction Behavior Analysis in Modern Banking Systems using Python

## 📌 Project Overview

This project focuses on analyzing banking transactions, digital payments, ATM usage, credit/debit card activity, and customer payment behavior using Python. The project applies data cleaning, exploratory data analysis (EDA), statistical analysis, and business-oriented visualizations to uncover insights into digital banking trends and transaction patterns across different banking sectors in India.

---

## 🎯 Project Objectives

- Maintain banking transaction information in a structured format.
- Reduce data inconsistencies and improve data quality.
- Monitor digital transactions, cash withdrawals, transaction values, and transaction volumes.
- Evaluate banking performance across bank categories and payment channels.
- Analyze customer preference towards digital payments versus cash transactions.

---

## 📊 Dataset Information

| Attribute | Details |
|------------|------------|
| Source | Indian Data Portal |
| Domain | Economy / Banking |
| Location | India |
| Timeline | 2022 – 2025 |
| Records | 2671 |
| Features | 30 Columns |

### Dataset Link

https://indiadataportal.com/p/reserve-bank-of-india/r/rbi-bankwise_atm_pos-in-mn-bx

---

## ❓ Problem Statement

Banks are rapidly moving toward digital payments such as UPI, QR payments, credit cards, and debit cards. This project aims to analyze:

1. Which banking sector is leading in digital transformation?
2. How customers use cash versus digital transactions?
3. Which bank categories perform better?
4. How ATM usage is changing?
5. Which payment channels contribute most to transaction value?
6. Which banking sector generates the highest total digital transaction value?
7. How can banks be segmented into low, medium, and high transaction categories?
8. How have digital transactions and cash withdrawal patterns changed over time?

---

## 🛠 Tools & Technologies

### Platform
- Google Colab

### Programming Language
- Python

### Libraries Used

#### Data Processing
- NumPy
- Pandas

#### Visualization
- Matplotlib
- Seaborn
- Plotly Express

#### Text Processing
- re

#### Warning Handling
- warnings

---

## 🧹 Data Preprocessing & Cleaning

### Steps Performed

- Duplicate record validation
- Missing value identification
- Hierarchical imputation
- Column renaming
- Data type verification
- Outlier detection
- Feature engineering

### Feature Engineering

#### Numerical Features

- Total Digital Transaction Value
- Cash Dependency Ratio

#### Categorical Features

- Digital Adoption Level
- Transaction Size Category

---

## 🔍 Exploratory Data Analysis (EDA)

### Activities Performed

- Dataset shape analysis
- Data type verification
- Statistical summary generation
- Missing value assessment
- Duplicate record validation
- Distribution analysis
- Transaction behavior exploration

### EDA Outcome

- Digital adoption levels identified
- Banking transaction patterns analyzed
- Cash dependency behavior evaluated
- Dataset quality validated

---

## 📈 Statistical Analysis

### Measure of Central Tendency

- Banking variables are highly positively skewed.
- Mean values exceed median values in most variables.
- Mode values are predominantly zero.
- Few banks dominate digital transaction activity.
- Cash dependency remains significant for some institutions.

### Variance & Standard Deviation

- High variability exists across transaction channels.
- UPI and online transactions show large spreads.
- Significant deviations from mean values are observed.
- Digital adoption varies considerably among banks.
- Cash dependency differs across institutions.

### Skewness & Kurtosis

- Financial variables exhibit heavy positive skewness.
- Transaction distributions are non-normal.
- Few banks contribute disproportionately large transaction values.
- Extreme observations create heavy-tailed distributions.
- High kurtosis reflects occasional transaction spikes.

---

## 📊 Visualizations

### Univariate Analysis

- UPI QR Distribution
- Total Digital Transaction Value Distribution
- Digital Adoption Level
- Transaction Size Category Analysis

### Bivariate Analysis

- Bank Category vs Total Digital Value
- UPI QR vs Total Digital Transaction Value
- Cash Dependency vs Digital Adoption
- Credit Card vs Debit Card Online Transactions

### Multivariate Analysis

- Bank Category, Transaction Size & Digital Value
- Online vs Offline Transaction Trends Over Time
- Sector-wise Online vs Offline Transaction Analysis
- Digital Transactions and Cash Withdrawal Trends Over Time

---

## 📌 Key Insights

- Private Sector Banks generated the highest digital transaction value.
- Higher digital adoption corresponds to lower cash dependency.
- UPI QR deployment positively impacts transaction performance.
- Credit card transactions contribute higher online transaction values.
- Digital transactions increased consistently between 2022 and 2025.

---

## 📊 Types of Analysis

### Descriptive Analysis

Banking transaction data shows strong digital adoption trends with highly skewed transaction distributions dominated by a few major banks.

### Diagnostic Analysis

Higher UPI QR deployment and digital adoption levels are associated with larger digital transaction values.

### Predictive Analysis

Digital transaction volumes are expected to continue increasing while cash dependency gradually declines.

### Prescriptive Analysis

Banks should strengthen digital infrastructure, expand QR-based payment systems, and improve customer digital engagement.

---

## 💡 Recommendations

- Expand UPI and QR payment infrastructure.
- Promote digital payment adoption through awareness programs.
- Strengthen digital banking services in underperforming banking sectors.
- Monitor high-performing transaction channels.
- Use transaction segmentation for strategic decision-making.
- Reduce dependency on cash-based services.

---

## 🚀 Future Enhancements

### Real-Time Banking Transaction Monitoring
Integrate live banking transaction feeds to monitor customer behavior and transaction trends in real time.

### Machine Learning-Based Transaction Forecasting
Develop predictive models to forecast transaction growth, digital adoption, and cash dependency.

### Advanced Banking Performance Analytics
Incorporate demographic, regional, and branch-level data for deeper banking analysis.

---

## ✅ Conclusion

This project analyzed banking transaction data to understand digital payment adoption, cash dependency, transaction behavior, and banking performance. The findings revealed that Private and Public Sector Banks play a major role in driving digital transactions, while UPI and online payment channels continue to grow rapidly. Overall, the study provides valuable insights to support data-driven decision-making in the banking sector.

---

## 👩‍💻 Author

**Kamali.K**
**Aspiring Data Analyst**
