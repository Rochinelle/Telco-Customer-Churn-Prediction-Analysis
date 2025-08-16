# Telco-Customer-Pediction

This project is a comprehensive analysis of customer churn within a telecommunications company. The goal is to build a predictive model that can identify customers at risk of leaving, allowing the business to take proactive steps to retain them.

##Project Workflow

### Exploratory Data Analysis (EDA)
- Visualized key patterns in customer behavior.
Found that customers with month-to-month contracts and low monthly charges are more likely to churn.
- Data Preprocessing
Handled missing values.
Encoded categorical variables into numerical format.
Normalized/standardized relevant features.
- Model Training & Evaluation
Trained machine learning models to predict churn.
Evaluated performance using accuracy, precision, recall, F1-score.
Interpreted feature importance with SHAP values.
- Business Recommendations
Focus retention efforts on new customers (highest churn in first 10 months).
Create special offers for customers with low charges.
Design campaigns for those with expiring contracts.

### Getting Started
- Requirements
Install the dependencies:
pip install -r requirements.txt
- Usage
Run the Jupyter notebook:
jupyter notebook churn.ipynb
-Results & Insights
The best-performing model achieved XX% accuracy and strong recall for churn cases.
Top churn drivers: contract type, tenure, monthly charges, and total charges.
Business can reduce churn by targeting at-risk customers with personalized retention offers.
  ### Dataset
The dataset used is the Telco Customer Churn dataset (Kaggle).
Link to dataset
https://www.kaggle.com/datasets/palashfendarkar/wa-fnusec-telcocustomerchurn/data

# Dashboard Preview
![Customer Churn Analysis Dashboard](https://github.com/user-attachments/assets/f9675061-d8d8-4368-9b7c-4e543e930256)


📜 License

This project is for educational purposes. Dataset belongs to Kaggle.
