# CreditCard-Fraud-Detection
EDA of Credit Card Transactions for Fraud Detection

### Project Overview  
This project conducts an **exploratory data analysis (EDA)** on a credit card transaction dataset to identify **fraudulent transactions**. The dataset, sourced from **Kaggle**, includes a mix of **legitimate** and **fraudulent** transaction records.

### Dataset Source  
**Kaggle Dataset**: Credit Card Fraud Detection  

### Dataset Summary  
- **Total Rows**: 284,807  
- **Total Columns**: 31  
- **Key Columns**:  
  - **Amount**: Represents the transaction amount (Float type).  
  - **Class**: Indicates whether a transaction is **legitimate (0)** or **fraudulent (1)** (Integer type).  
- Other columns consist of various transaction features such as time and transaction numbers, primarily in float format.  

### Data Quality  
- **Missing Values**: No missing or null values were detected in the dataset.  

### Transaction Analysis  
- **Legitimate Transactions**: 284,315  
- **Fraudulent Transactions**: 492  
- **Fraudulent Transaction Percentage**: Fraudulent transactions account for approximately **0.17%** of the total dataset.  

### Statistical Summary for 'Amount'  
- **Minimum**: 0.0  
- **Maximum**: 25,691.16  
- **Mean**: 88.35  
- **Median**: 22.0  

### Transaction Amount Insights  
- **Maximum Transaction Amount**: 25,691.16  
- **Fraudulent or Legitimate?**: The transaction with the maximum amount is **legitimate**.  

### Visualization  
1. **Bar Chart for Transaction Count**:  
   - While it is feasible to create a bar chart for fraudulent vs. legitimate transactions, it may not be effective due to the **high imbalance** in the data, as fraudulent transactions are significantly fewer.  

2. **Histogram of Transaction Amounts**:  
   - The histogram shows that most transaction amounts lie between **0 to 5,000**. The distribution is **right-skewed**, with the tail extending toward higher transaction amounts.  

### Correlation Analysis  
- A **heatmap** for correlation analysis is not ideal for this dataset due to the lack of correlation between many transaction-related columns, such as time and transaction numbers.  
- Instead, a **scatter plot** offers a more effective visualization for exploring relationships among numerical features.  
