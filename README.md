# Customer_Churn_Prediction-
A machine learning project focused on analyzing and predicting customer churn using the Telco dataset. Includes data preprocessing, exploratory data analysis (EDA), and predictive modeling to identify at-risk customers.

📌 Project Overview
This project focuses on analyzing telecom customer data to predict customer churn. The primary goal is to identify customers who are likely to discontinue their service, enabling the company to take proactive retention measures.

The project follows a full data science pipeline, including:

Data Preparation & Cleaning: Handling missing values and ensuring data integrity.

Feature Engineering: Converting categorical variables into numerical formats for machine learning readiness.

Predictive Modeling: Building and evaluating machine learning models to forecast churn.

📊 Dataset Description
The dataset used in this project consists of 7,043 customer records with 21 different features. Key attributes include:

Demographics: Gender, Senior Citizen status, Partners, and Dependents.

Services: Phone service, multiple lines, internet service, online security, online backup, device protection, tech support, and streaming services.

Account Information: Tenure, contract type, paperless billing, payment method, monthly charges, and total charges.

Target Variable: Churn (indicates whether the customer left within the last month).

🛠️ Technical Implementation
Task 1: Data Preparation
Handling Missing Values: Conducted a thorough check for null values across all 21 columns to ensure a clean dataset.

Data Transformation: Removed unnecessary columns like customerID and addressed data type inconsistencies.

Encoding: Categorical variables were transformed into numerical formats using encoding techniques to prepare them for model training.

Task 2: Machine Learning Modeling
(You can add the specific models you used here, such as Logistic Regression, Random Forest, or XGBoost, based on the final version of your notebook.)

📈 Performance Results
The model was evaluated using several key metrics to ensure its reliability in identifying at-risk customers:

ROC-AUC Score: 68.66%

Recall: 47.86%

F1-Score: (Insert the final F1 score calculated in your notebook here)

🚀 How to Run the Project
Clone this repository:

Bash
git clone https://github.com/TANIYA-14/customer-churn-prediction.git
Install the required dependencies:

Bash
pip install pandas numpy scikit-learn
Open the Jupyter notebook CustomerChurnAnalysisandPrediction.ipynb to view the analysis and run the models.

🧰 Tools & Libraries Used
Python: Core programming language.

Pandas & NumPy: Data manipulation and numerical computation.

Scikit-Learn: Machine learning model building and evaluation metrics.

Author
Taniya Mondal

LinkedIn: www.linkedin.com/in/taniya-mondal-293827351
