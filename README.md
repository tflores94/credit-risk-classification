# credit-risk-classification
Assignment 20
# Purpose of the Analysis
The analysis aims to predict whether a loan is likely to default based on historical data. The analysis uses machine learning to classify loans as high-risk(defaulted or '1') or healthy (non-defaulted or '0'). This prediction will help the company asses which loans requires more attention and minimize potential losses.

# Financial Information and Prediction Goal
The dataset contains financial information regarding loan applicants, such as:
loan amount, application's income, credit score, and previous loan history. The target variable to predict is loan_status, which contains two possible values '0"- healthy loan, '1'- high-risk loan.

# Variable Information
The loan_status column is our target variable, while the remaining columns represent our features, such as the loan amount, income, and credit score. According to our dataset, about 82% were indicated as high-risk loans. 

# Stages of the Machine Learning Process
1. Data Preprocessing
    - I loaded the dataset and examined the features.
    - I split the data into training and testing sets, ensuring I maintained class balance.
2. EDA: Visualizations and statistical summaries were used to understand the distribution and relationships between features.
3. Feature Selection: key variables were identified that significantly contribute to predicting credit risk.
4. Model Training and Evaluation: Several other models were used, like logistic regression and other classification techniques.

# Methods Used:
Multiple methods were used throughout the analysis. For example, I used a logistic regression model as a baseline classifier. Other models were used to capture more complex patterns in the data.

# Results
- Machine learning model 1: Logistic Regression
   Accuracy: achieved an accuracy score of 85%
   Precision: The model obtained a precision of 82%, indicating a high proportion of correctly identifying risky cases.
   Recall: the score was close to 78%, reflecting the model's ability to correclty capture the majority of actual risky cases.

 # Summary
Based on the performance metrics and the benefits of simplicity and interoperability, the Logistic Regression model is recommended for this credit risk classification task. Its transparent decision-making process is particularly advantageous in financial contexts, where understanding the model’s reasoning is as important as achieving high performance. Its lower complexity reduces the risk of overfitting, ensuring more stable predictions in real-world applications.The Logistic Regression model demonstrates more consistent and interpretable performance across key metrics. If minimizing the risk of incorrectly approving high-risk applicants is a priority, Logistic Regression’s balanced recall helps ensure that most high-risk cases are flagged. For scenarios where it’s critical to avoid misclassifying low-risk applicants as high-risk, the clear interpretability of Logistic Regression allows for straightforward adjustments and threshold tuning based on business needs. In conclusion, the Logistic Regression model is recommended due to its interpretability, balanced performance, and suitability for financial risk assessments.






