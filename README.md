# 🚑 Health Insurance Cost Prediction using Machine Learning

<div align="center">

### Predicting Insurance Premiums with Machine Learning

[🌐 Live Demo](https://insurancepredictions-sanjana.streamlit.app/) •
[📂 GitHub Repository](https://github.com/sanjanamali17/insurance_predictions)

</div>

---

## 📌 Overview

Health insurance companies determine premiums using multiple factors such as age, BMI, smoking habits, family size, and geographical region.

This project leverages Machine Learning algorithms to predict insurance costs accurately and provides an interactive web application for real-time premium estimation.

The project demonstrates a complete end-to-end Machine Learning workflow:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Model Training
- Model Evaluation
- Model Deployment using Streamlit

---

## 🎯 Business Problem

Insurance providers need accurate methods to estimate healthcare expenses while minimizing underwriting risk.

Traditional premium calculations can be time-consuming and inconsistent.

This solution helps:

- Predict medical insurance expenses
- Support premium pricing decisions
- Identify high-risk customers
- Automate cost estimation

---

## 🌐 Live Application

### Try it here:

👉 **https://insurancepredictions-sanjana.streamlit.app/**

### Sample Prediction

| Input Feature | Value |
|--------------|--------|
| Age | 30 |
| BMI | 25 |
| Children | 0 |
| Gender | Female |
| Smoker | No |
| Region | Northeast |

### Predicted Insurance Cost

```text
₹ 5,676.13
```

---

## 📊 Dataset Information

The dataset contains customer demographic and health-related information.

### Features

| Feature | Description |
|----------|------------|
| Age | Age of the individual |
| Sex | Gender |
| BMI | Body Mass Index |
| Children | Number of dependents |
| Smoker | Smoking status |
| Region | Residential region |
| Expenses | Insurance charges (Target Variable) |

### Dataset Statistics

| Metric | Value |
|----------|--------|
| Total Records | 1,338 |
| Features | 6 |
| Target Variable | Expenses |
| Missing Values | 0 |
| Duplicate Records Removed | 1 |

---

## 🔍 Exploratory Data Analysis

### Univariate Analysis

- Smoker Distribution
- Gender Distribution
- Region Distribution
- Children Distribution
- Age Distribution

### Bivariate Analysis

- Age vs Expenses
- BMI vs Expenses
- Smoker vs Expenses

### Multivariate Analysis

- Correlation Heatmap
- Feature Relationship Analysis

---

## 💡 Key Insights

### 🚬 Smoking Status is the Strongest Predictor

Smokers have significantly higher insurance expenses compared to non-smokers.

### 📈 Age Positively Impacts Insurance Cost

Insurance charges generally increase with age.

### ⚖️ BMI Influences Premium Amount

Higher BMI values are associated with increased healthcare expenses.

### 👨‍👩‍👧 Family Size Shows Moderate Impact

The number of dependents affects insurance costs but less strongly than smoking status.

---

## ⚙️ Data Preprocessing

### Data Cleaning

- Checked for missing values
- Removed duplicate records
- Verified dataset integrity

### Feature Engineering

Categorical variables were converted into numerical representations using:

```python
pd.get_dummies(drop_first=True)
```

### Feature Scaling

Applied Min-Max Scaling:

```python
MinMaxScaler()
```

Range:

```text
[0,1]
```

---

## 🤖 Machine Learning Models

The following regression algorithms were trained and evaluated:

### 1. Linear Regression

- Baseline Model

### 2. Polynomial Regression

- Captures non-linear relationships

### 3. Decision Tree Regression

- Tree-based learning approach

### 4. Support Vector Regression

- Margin-based regression

### 5. Random Forest Regression

- Ensemble learning technique

---

## 📈 Model Performance

| Model | R² Score |
|---------|-----------|
| Linear Regression | 75% |
| Polynomial Regression | 86% |
| Decision Tree Regression | 73% |
| Support Vector Regression | 15% |
| Random Forest Regression | **88%** |

---

## 🏆 Best Model

### Random Forest Regressor

```python
RandomForestRegressor(
    n_estimators=10
)
```

### Performance Metrics

| Metric | Value |
|----------|--------|
| Best Model | Random Forest Regressor |
| R² Score | 88% |
| Training Strategy | Ensemble Learning |
| Prediction Time | Less than 1 Second |

---

## 🔄 Prediction Workflow

```text
User Input
     │
     ▼
Data Validation
     │
     ▼
Feature Engineering
     │
     ▼
Feature Scaling
     │
     ▼
Random Forest Model
     │
     ▼
Insurance Cost Prediction
     │
     ▼
Result Display
```

---

## 🛠️ Technology Stack

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn

### Deployment

- Streamlit

### Model Serialization

- Pickle

---

## 📂 Project Structure

```bash
insurance_predictions/
│
├── insurance.csv
├── app.py
├── RF_model.pkl
├── scalar.pkl
├── requirements.txt
├── README.md
│
└── notebooks/
    └── insurance_prediction.ipynb
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/sanjanamali17/insurance_predictions.git
```

Move into the project directory:

```bash
cd insurance_predictions
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📊 Project Metrics

| Metric | Achievement |
|----------|------------|
| Dataset Records | 1,338 |
| Features Engineered | 8 |
| Models Compared | 5 |
| Best Model Accuracy | 88% |
| Missing Values | 0 |
| Deployment Platform | Streamlit |
| Prediction Speed | < 1 Second |

---

## 🎓 Skills Demonstrated

This project showcases:

- Data Cleaning
- Data Visualization
- Exploratory Data Analysis
- Feature Engineering
- Feature Scaling
- Regression Modeling
- Model Evaluation
- Hyperparameter Understanding
- Model Deployment
- End-to-End Machine Learning Pipeline

---

## 🔮 Future Enhancements

- XGBoost Regression
- LightGBM
- CatBoost
- Hyperparameter Optimization
- Cross Validation
- SHAP Explainability
- Insurance Risk Scoring
- Cloud Deployment (AWS/GCP/Azure)

---

## 👩‍💻 Author

### Sanjana Mali

AI & Data Science Engineer

**GitHub:** https://github.com/sanjanamali17

**Live Application:** https://insurancepredictions-sanjana.streamlit.app/

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.

It helps increase visibility and supports future development.

⭐ Star the repository if you like the project.
