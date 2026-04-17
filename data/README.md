# Customer Churn Prediction using Machine Learning

## Project Summary
This project builds a complete machine learning pipeline to predict customer churn in a telecommunications company. The goal is to identify customers at risk of leaving and understand the main drivers of churn so the business can take preventive actions.

The repository contains the full workflow from raw data to model evaluation and interpretation.


## Business Problem
Customer acquisition is significantly more expensive than customer retention. Being able to anticipate churn allows companies to:

- Identify high-risk customers early  
- Design targeted retention campaigns  
- Reduce revenue loss  
- Improve long-term customer value  

This project frames churn prediction as a supervised binary classification problem.


## Dataset Description
The dataset includes customer demographic information, subscription details, service usage, and billing data.

### Feature groups

**Customer profile**
- Gender  
- Senior citizen status  
- Partner / dependents  

**Account information**
- Contract type  
- Tenure  
- Payment method  
- Paperless billing  

**Services**
- Internet service  
- Online security / backup  
- Device protection  
- Tech support  
- Streaming services  

**Financial**
- Monthly charges  
- Total charges  

**Target variable**
- Churn (Yes / No)


## Project Structure
customer-churn-prediction/


## Methodology

### 1. Data Cleaning and Preparation
The preprocessing pipeline includes:

- Handling missing values  
- Converting data types  
- Removing inconsistencies  
- Encoding categorical variables  
- Feature scaling for numerical variables  
- Train/test split  

### 2. Exploratory Data Analysis
Exploration focuses on understanding how churn relates to customer behavior and subscription characteristics.

Key questions investigated:

- Which contract types are most associated with churn?  
- Does tenure reduce churn risk?  
- Do additional services improve retention?  
- How do monthly charges relate to churn?  

### 3. Feature Engineering
Transformations applied:

- One-Hot Encoding of categorical variables  
- Standardization of numeric features  
- Preparation of data for model training  

### 4. Models Trained
Several classification models were trained and compared:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

### 5. Evaluation Metrics
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  

These metrics were chosen to balance overall performance with the ability to correctly identify churned customers.


## Key Findings
The analysis highlights several strong churn indicators:

- Month-to-month contracts show the highest churn risk  
- Customers with short tenure are more likely to churn  
- Lack of additional services (security, backup, tech support) correlates with higher churn  
- Higher monthly charges are associated with increased churn probability  

These insights can guide targeted retention strategies.


## How to Run the Project

### 1. Clone the repository
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the notebook
Open the Jupyter notebook and run all cells.


## Future Improvements
Potential extensions include:

- Hyperparameter tuning  
- Model explainability (SHAP / feature attribution)  
- Deployment as an API  
- Dashboard for business stakeholders  


## Author
Andrés Pi González
