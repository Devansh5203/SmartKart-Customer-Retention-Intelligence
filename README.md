🛒 SmartKart Customer Churn Prediction
Industry-Grade Machine Learning Pipeline for Customer Retention
SmartKart Customer Churn Prediction is an end-to-end Machine Learning project that predicts customers who are likely to leave the SmartKart platform. The project demonstrates a complete ML workflow, including data cleaning, outlier treatment, feature selection, model training, evaluation, interpretation, and customer-risk identification.

📌 Project Overview
Customer churn is a major challenge for retail and e-commerce businesses. Identifying customers at risk of leaving allows companies to take proactive retention actions.

This project uses customer-level data such as:

Age
Monthly Spend
Complaints
Churn Status
A Logistic Regression model is trained to predict whether a customer is likely to churn.

🎯 Business Objective
The primary objective is to:

Identify customers who are at high risk of churn so that SmartKart can take proactive customer-retention actions.

Potential business actions include targeted offers, personalized communication, improved customer support, and loyalty programs.

🔄 Machine Learning Pipeline
The project follows a complete 15-step ML pipeline:

Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Outlier Detection & Treatment
      ↓
Feature Selection
      ↓
Target Definition
      ↓
Target Encoding
      ↓
Train-Test Split
      ↓
Feature Standardisation
      ↓
Model Building
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Model Interpretation
      ↓
Final Business Output
🧹 Data Quality & Preprocessing
The dataset intentionally contains real-world data-quality problems such as:

Duplicate customer records
Missing values
Extra whitespace
Incorrect data types
Invalid ages
Negative spending values
Extreme spending outliers
Unrealistic complaint counts
The preprocessing pipeline handles these issues using:

Duplicate removal
Data-type conversion
Invalid-value treatment
Median imputation
IQR-based outlier detection
Outlier capping
The original dataset contains 100 customer records and 5 columns. After removing duplicate records, the cleaned dataset contains 95 records.

🧠 Features Used
The model uses three business-relevant features:

Feature	Description
Age	Customer age
Monthly_Spend	Customer's monthly spending
Complaints	Number of customer complaints
Customer_ID is excluded from model training because it is an identifier rather than a predictive feature.

Target Variable
Churn

0 → Customer did not churn
1 → Customer churned
🤖 Machine Learning Model
Logistic Regression
Logistic Regression is used as the primary classification model because the objective is to predict a binary outcome:

Customer → Churn / No Churn
The dataset is divided using an 80/20 train-test split, with stratification and random_state=42 for reproducibility.

📊 Model Evaluation
The model evaluation process includes classification metrics and visual analysis to understand predictive performance.

Key evaluation concepts include:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
These metrics help determine how effectively the model identifies customers who are likely to churn.

💼 Business Value
The project converts Machine Learning predictions into actionable business insights.

SmartKart can use the predictions to:

🎯 Identify high-risk customers
📩 Launch targeted retention campaigns
🎁 Provide personalized offers
📞 Prioritize customer support
📈 Improve customer retention
💰 Reduce potential revenue loss
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab
Jupyter Notebook
📁 Project Structure
SmartKart-Customer-Churn-Prediction/
│
├── SmartKart_Churn_Prediction_ML_Pipeline.ipynb
├── SmartKart_dirty_100_rows.csv
├── README.md
└── requirements.txt
🚀 How to Run
1. Clone the repository
git clone https://github.com/your-username/SmartKart-Customer-Churn-Prediction.git
2. Open the notebook
Open:

SmartKart_Churn_Prediction_ML_Pipeline.ipynb
using Jupyter Notebook or Google Colab.

3. Upload the dataset
Upload:

SmartKart_dirty_100_rows.csv
4. Run the notebook
Run all cells from beginning to end to reproduce the complete ML pipeline.

📌 Key Learning Outcomes
This project demonstrates practical understanding of:

Data preprocessing
Data quality management
Exploratory data analysis
Outlier treatment
Feature selection
Classification
Logistic Regression
Model evaluation
Model interpretation
Business-oriented ML applications
🔮 Future Enhancements
The project can be further improved by:

Testing Random Forest, XGBoost, and other classification models
Hyperparameter tuning
Cross-validation
Feature engineering
Model explainability using SHAP
Customer churn probability scoring
Interactive Power BI/Tableau dashboard
Deployment using Streamlit or Flask
Automated customer-retention recommendations
👨‍💻 Project Author
Chanpreet Singh Dhiman

BBA Fintech & AI Chitkara Business School

Areas of Interest: AI • Machine Learning • Data Analytics • FinTech • Automation

⭐ Project Highlights
A complete business-focused Machine Learning pipeline that transforms messy customer data into actionable churn predictions for customer-retention decision making.

If you find this project useful, consider ⭐ starring the repository.
