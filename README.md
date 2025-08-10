# Online-Payment-Fraud-Detection

This project aims to build an effective machine learning system to detect fraudulent transactions within an online payment dataset. Fraud detection in financial transactions is a crucial task to prevent monetary losses and protect users from malicious activities. Using real-world transaction data, this project demonstrates a practical approach to identifying fraud by analyzing key transaction attributes and applying supervised learning techniques.

The dataset comprises detailed transactional information including transaction types, monetary amounts, and account balances before and after each transaction. By encoding categorical data and leveraging numerical features, a Decision Tree classification model is trained to distinguish between legitimate and fraudulent transactions.

##  Key Technologies Used

- **Python** – Programming language used for the entire project.
- **Pandas** – For loading, cleaning, and manipulating the dataset.
- **NumPy** – For numerical computations and handling arrays for ML input.
- **Plotly Express** – For creating interactive visualizations (e.g., donut/pie charts).
- **scikit-learn** – For machine learning tasks such as train-test split, Decision Tree classification, and evaluation.
- **scikit-learn Metrics** – For model evaluation using accuracy, precision, recall, F1-score, and confusion matrix.

- ##  Data Source Information

The dataset used in this project is sourced from a publicly available online payments fraud detection dataset, which simulates real-world online financial transactions.

### What the data contains:
- **Transaction Details:**  
  - `step`: The time step of the transaction (unit of time elapsed).  
  - `type`: Type of transaction (e.g., PAYMENT, CASH_OUT, TRANSFER, CASH_IN, DEBIT).  
  - `amount`: The monetary amount involved in the transaction.  
  - `nameOrig`: The originator's account ID.  
  - `oldbalanceOrg`: The starting balance of the originator before the transaction.  
  - `newbalanceOrig`: The ending balance of the originator after the transaction.  
  - `nameDest`: The recipient's account ID.  
  - `oldbalanceDest`: The starting balance of the recipient before the transaction.  
  - `newbalanceDest`: The ending balance of the recipient after the transaction.  

- **Fraud Labels:**  
  - `isFraud`: Binary label indicating whether the transaction is fraudulent (1) or legitimate (0).  
  - `isFlaggedFraud`: Indicator for transactions flagged by the system as fraud (not directly used in this project).  

This rich transactional data allows for supervised learning to detect fraudulent activities based on patterns in transaction type, amount, and account balances.

## Features and Highlights

- **Data Preprocessing:** Maps transaction types to numeric labels and fraud indicators to readable strings for better machine learning compatibility and interpretability.
- **Feature Selection:** Uses transaction type, transaction amount, and sender’s account balances before and after the transaction for modeling.
- **Modeling:** Implements a Decision Tree classifier to distinguish fraudulent transactions.
- **Model Evaluation:** Reports accuracy, precision, recall, F1-score, and confusion matrix to provide a detailed view of model effectiveness.
- **Visualization:** Includes an interactive donut pie chart to visualize the distribution of transaction types with Plotly Express.
- **Sample Prediction:** Demonstrates prediction on example transaction data.

- ##  Impact and Insights

- **Financial Security Enhancement:**  
  Helps detect fraudulent transactions, reducing financial losses for businesses and customers. Early and accurate fraud detection mitigates risks and fosters trust in online payment systems.

- **Improved Fraud Detection Capabilities:**  
  Uses machine learning techniques tailored for imbalanced data, such as a Decision Tree classifier with precision, recall, and F1-score evaluation, going beyond simple accuracy to reliably detect fraud.

- **Data-Driven Decision Making:**  
  Interactive visualization of transaction types and detailed model evaluation metrics empower stakeholders to understand transaction patterns and model performance for informed fraud prevention strategies.

- **Scalability and Extensibility:**  
  Modular workflow—from preprocessing and feature selection to model training and evaluation—allows easy integration of more data, advanced algorithms, and enhancements to boost performance.

- **Real-World Applicability:**  
  Sample prediction functionality shows practical usage for real-time fraud detection applications, demonstrating how the model can be deployed in financial systems.

- **Insights on Transaction Patterns:**  
  Analysis of transaction type distribution reveals prevalent categories, helping target monitoring efforts on higher-risk transaction types.




