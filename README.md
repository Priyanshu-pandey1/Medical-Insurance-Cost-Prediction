# Medical Insurance Cost Prediction 🏥

A Machine Learning project developed to predict the individual medical costs billed by health insurance based on various patient attributes. This model uses **Linear Regression** to analyze the relationship between factors like age, BMI, and smoking status to estimate healthcare expenses.

## 🚀 Project Overview
The goal of this project is to build a predictive model that can accurately estimate medical insurance premiums. By leveraging the **Medical Insurance Dataset**, we perform Exploratory Data Analysis (EDA) and apply regression techniques to understand the key drivers of insurance costs.

## 🛠️ Tech Stack
The following libraries and tools were used to build this project:
* **Python** (Core Language)
* **NumPy** & **Pandas** (Data Manipulation)
* **Matplotlib** & **Seaborn** (Data Visualization)
* **Scikit-learn** (Model Training & Evaluation)

## 📊 Dataset Insights
The dataset contains information on **1,338** individuals. 
* **Smoker Distribution:**
  * Non-smokers: 1,064
  * Smokers: 274
* **Features:** Age, Sex, BMI, Children, Smoker status, and Region.

## 🧠 Model Performance
The model was trained and evaluated using the **R-squared ($R^2$)** metric, which measures the proportion of variance for the dependent variable that's explained by the independent variables.

| Metric | Score |
| :--- | :--- |
| **R-squared (Training)** | 0.7515 |
| **R-squared (Testing)** | 0.7447 |

## 📁 Repository Structure
```text
├── Medical_Insurance_Cost_Prediction.ipynb  # Main Python code
├── insurance.csv                            # Dataset
└── README.md                                # Project Documentation
