# Customer Churn Prediction
## Project Overview

Customer churn prediction is an important problem for telecom companies. This project builds a machine learning model to predict whether a customer will leave the service or stay. Early identification of churn helps companies improve customer retention strategies and reduce revenue loss.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Power BI

## Dataset

The project uses the **Telco Customer Churn dataset**, which contains customer information such as gender, tenure, contract type, monthly charges, and whether the customer churned.

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Data Visualization
5. Feature Encoding
6. Train Logistic Regression 
7. Train Random Forest
8. Evaluate Models using ROC-AUC
9. Simulate Retention Strategy
10. Predict Churn Probability

## Machine Learning Models

* Logistic Regression
* Random Forest Classifier

## Evaluation Metric

The model performance is evaluated using **ROC-AUC score**, which measures how well the model distinguishes between churn and non-churn customers.

## Results

Random Forest generally performs better than Logistic Regression for this dataset, providing higher ROC-AUC scores and better prediction accuracy.

## Business Insight

Customers with high churn probability can be targeted with retention strategies such as:

* Discount offers
* Improved customer support
* Loyalty programs

## Visualization

Data visualization is used to analyze:

* Customer Churn distribution
* Churn by Contract
* Monthly charges distribution
* Monthly Charges vs Churn

## Dashboard

The predicted churn results are exported to CSV and visualized in **Power BI** to create an interactive dashboard for business analysis.

## Author

C. Ishwarya Lakshmi

## License

This project is for educational and academic purposes.
