🚑 Health Insurance Cost Prediction using Machine Learning
<div align="center">
Predict Insurance Premiums with Data-Driven Intelligenc


🌐 Live Application

https://insurancepredictions-sanjana.streamlit.app/

📂 GitHub Repository

https://github.com/sanjanamali17/insurance_predictions

</div>
📌 Project Overview

Health insurance companies calculate premiums based on multiple factors including age, BMI, smoking habits, family size, and geographical region. Estimating these costs manually is often inconsistent and inefficient.

This project leverages Machine Learning algorithms to predict insurance expenses with high accuracy, helping insurers make data-driven decisions and enabling customers to estimate future healthcare costs.

The project follows a complete end-to-end Machine Learning workflow:

✅ Data Cleaning
✅ Exploratory Data Analysis (EDA)
✅ Feature Engineering
✅ Feature Scaling
✅ Model Training
✅ Model Evaluation
✅ Model Deployment using Streamlit

🎯 Business Problem

Insurance providers need reliable premium estimation models to:

Reduce underwriting risk
Improve pricing accuracy
Automate premium calculations
Enhance customer experience
Identify high-risk customers

This solution predicts expected insurance charges based on customer characteristics.

📊 Dataset Information
Attribute	Description
Age	Age of the customer
Sex	Male/Female
BMI	Body Mass Index
Children	Number of dependents
Smoker	Smoking status
Region	Residential region
Expenses	Medical insurance charges (Target)
Dataset Statistics
Metric	Value
Total Records	1,338
Features	6
Target Variable	Expenses
Missing Values	0
Duplicate Records Removed	1
🔍 Exploratory Data Analysis

Comprehensive analysis was performed to uncover relationships between features and insurance costs.

Univariate Analysis
Gender Distribution
Smoker Distribution
Regional Distribution
Children Count Analysis
Age Distribution
Bivariate Analysis
Age vs Expenses
BMI vs Expenses
Smoker vs Expenses
Multivariate Analysis
Correlation Heatmap
Feature Relationships
💡 Key Insights
🚬 Smoking Has the Highest Impact

Smokers incur significantly higher medical expenses compared to non-smokers.

📈 Age Increases Insurance Cost

Insurance expenses tend to rise with age.

⚖️ BMI Influences Premiums

Higher BMI values are associated with increased healthcare costs.

👨‍👩‍👧 Family Size Has Moderate Impact

The number of children affects expenses but less strongly than smoking or age.

⚙️ Machine Learning Pipeline
Data Preprocessing
Handling Duplicates
df.drop_duplicates(inplace=True)
Encoding Categorical Features
pd.get_dummies(drop_first=True)
Feature Scaling

Min-Max Scaling

MinMaxScaler()

Range:

[0,1]
🤖 Models Trained
Model	Purpose
Linear Regression	Baseline Model
Polynomial Regression	Captures Non-Linear Patterns
Decision Tree Regression	Rule-Based Learning
Support Vector Regression	Margin-Based Regression
Random Forest Regression	Ensemble Learning
🏆 Model Performance
Model	R² Score (%)
Linear Regression	75%
Polynomial Regression	86%
Decision Tree Regression	73%
Support Vector Regression	15%
Random Forest Regression	88%
🥇 Best Performing Model
Random Forest Regressor
RandomForestRegressor(
    n_estimators=10
)
Final Performance
Metric	Value
Best Model	Random Forest Regressor
R² Score	88%
Training Strategy	Ensemble Learning
Deployment	Streamlit
🚀 Live Demo

Try the application instantly:

🔗 Streamlit Application

https://insurancepredictions-sanjana.streamlit.app/

Example Prediction:

Input	Value
Age	30
BMI	25
Children	0
Gender	Female
Smoker	No
Region	Northeast
Predicted Insurance Cost
₹ 5,676.13
🛠️ Tech Stack
Programming Language
Python
Data Analysis
Pandas
NumPy
Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-Learn
Deployment
Streamlit
Model Serialization
Pickle
📂 Project Structure
insurance_predictions/
│
├── data/
│   └── insurance.csv
│
├── notebooks/
│   └── insurance_prediction.ipynb
│
├── models/
│   ├── RF_model.pkl
│   └── scalar.pkl
│
├── app.py
├── requirements.txt
├── README.md
│
└── assets/
    └── screenshots
🔮 Prediction Workflow
User Input
    ↓
Feature Validation
    ↓
Data Preprocessing
    ↓
Feature Scaling
    ↓
Random Forest Model
    ↓
Insurance Cost Prediction
    ↓
Result Display
📈 Future Improvements
Model Improvements
XGBoost Regressor
CatBoost Regressor
LightGBM
Hyperparameter Tuning
Cross Validation
Product Improvements
Premium Comparison Dashboard
Risk Score Analysis
SHAP Explainability
Insurance Recommendation Engine
Cloud Deployment (AWS/GCP/Azure)
🎓 Skills Demonstrated

This project showcases:

Data Cleaning
Data Visualization
Exploratory Data Analysis
Feature Engineering
Feature Scaling
Regression Modeling
Model Comparison
Model Deployment
End-to-End Machine Learning Pipeline
📊 Project Metrics
<div align="center">
Metric	Achievement
Dataset Records	1,338
Features Processed	8
ML Models Compared	5
Best R² Score	88%
Missing Values	0
Deployment Platform	Streamlit
Model Type	Random Forest
Prediction Time	< 1 Second
</div>
🌟 Why This Project Stands Out

✔ End-to-End Machine Learning Implementation

✔ Multiple Model Benchmarking

✔ Real-Time Prediction Interface

✔ Production-Ready Deployment

✔ Business-Oriented Use Case

✔ Interactive Streamlit Application

✔ Strong EDA and Feature Engineering

✔ Demonstrates Industry-Relevant ML Skills

👩‍💻 Author
Sanjana Mali

AI & Data Science Engineer

Machine Learning
Data Science
Artificial Intelligence
Predictive Analytics
Connect
GitHub: https://github.com/sanjanamali17
Live App: https://insurancepredictions-sanjana
