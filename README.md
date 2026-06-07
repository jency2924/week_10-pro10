Credit Card Fraud Detection System
Project Overview

This project focuses on analyzing credit card transactions to identify fraudulent activities using Exploratory Data Analysis (EDA), Data Visualization, Risk Analysis, and Machine Learning techniques.

The system helps financial institutions understand transaction patterns, detect suspicious behavior, and support fraud prevention strategies.

Objectives
Collect and analyze credit card transaction data.
Clean and preprocess the dataset.
Perform descriptive statistical analysis.
Study fraud and non-fraud transaction behavior.
Analyze feature relationships using correlation.
Visualize transaction patterns and fraud distribution.
Categorize transactions based on risk levels.
Build a predictive model using Linear Regression.
Evaluate model performance.
Create interactive dashboards for insights.
Dataset

Dataset Name: Credit Card Fraud Synthetic Dataset

File Used:

credit_card_fraud_synthetic.csv
Expected Important Columns
Column Name	Description
Time	Transaction timestamp
Amount	Transaction amount
Class	Fraud Label (0 = Normal, 1 = Fraud)
Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-Learn
Project Workflow
1. Data Collection
Load dataset from Google Drive.
Verify dataset structure.
2. Data Cleaning
Check missing values.
Remove duplicate records.
Handle null values.
Verify data types.
3. Descriptive Statistics
Dataset summary.
Average transaction amount.
Fraud percentage calculation.
4. Fraud Behavior Analysis
Compare fraud and normal transactions.
Analyze transaction amount statistics.
5. Group-Based Analysis
Amount vs Fraud.
Time vs Fraud.
Feature pattern analysis.
6. Relationship Analysis
Correlation Matrix.
Feature importance through correlation.
7. Data Visualization
Fraud distribution chart.
Transaction amount histogram.
Scatter plots.
Boxplots.
Correlation heatmaps.
8. Risk Analysis

Transactions are categorized as:

Amount Range	Risk Level
Less than 100	Low Risk
100 to 999	Medium Risk
1000 and above	High Risk
9. Predictive Modeling
Train-Test Split
Linear Regression Model
Prediction Generation
10. Model Evaluation
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Residual Analysis
11. Interactive Dashboard

Using Plotly:

Fraud Distribution Dashboard
Transaction Trend Dashboard
Fraud Comparison Dashboard
Correlation Heatmap Dashboard
Risk Distribution Dashboard
Machine Learning Model
Algorithm Used

Linear Regression

Input Feature
Time
Target Variable
Amount
Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Key Insights
Fraud transactions are significantly lower than normal transactions.
Higher transaction amounts tend to show increased fraud risk.
Correlation analysis helps identify important fraud-related features.
Risk categorization assists in detecting suspicious transactions quickly.
Visualizations provide better understanding of transaction behavior.
Results

The project successfully:

Analyzed transaction patterns.
Identified fraud-related behaviors.
Categorized transactions into risk levels.
Built a predictive model for transaction amount prediction.
Generated visual and interactive dashboards for better decision-making.
Future Enhancements
Implement classification models such as:
Logistic Regression
Random Forest
XGBoost
Gradient Boosting
Neural Networks
Deploy the model using:
Flask
Streamlit
Django
Integrate real-time fraud detection.
Build a complete web-based dashboard

DATA visulitation

Countplot
<img width="437" height="377" alt="image" src="https://github.com/user-attachments/assets/9ede4e23-631d-46be-bcbc-59b6cc4af2be" />
 histogram
 <img width="545" height="370" alt="image" src="https://github.com/user-attachments/assets/64fdc490-a247-4920-b212-1b9b2c4cf9a4" />
Scatter plot
<img width="576" height="375" alt="image" src="https://github.com/user-attachments/assets/e4f6b645-7cc9-4248-aa83-e31e49e74224" />
Box plot
<img width="570" height="388" alt="image" src="https://github.com/user-attachments/assets/cac7cd74-e8e9-4d65-93c5-f088ad5d4c36" />
heatmap
<img width="830" height="637" alt="image" src="https://github.com/user-attachments/assets/5301a342-f686-4a96-afc6-3f7a8a84ca2f" />
Risk level visualization
<img width="515" height="383" alt="image" src="https://github.com/user-attachments/assets/aa348928-9706-405e-9f80-7a88839779c1" />

Conclusion

The Credit Card Fraud Detection System demonstrates how data analytics and machine learning can be used to analyze financial transactions and identify suspicious activities. Through EDA, visualization, risk assessment, and predictive modeling, the project provides valuable insights that can help financial institutions strengthen fraud prevention and improve transaction security.
