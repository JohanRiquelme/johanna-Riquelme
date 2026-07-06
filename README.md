# johanna-Riquelme

# 🤖 Predictive Data Analytics Project: Lab2 Task 2
### Python Diploma Portfolio Piece | CCT College Dublin (Summer 2026)

## 📌 Project Overview
This repository contains the end-to-end data science workflow developed for my Python Diploma in Predictive Data Analytics. 
The project focuses on taking a raw, messy enterprise dataset, cleaning and engineering features, and building a predictive model to solve a core business problem: 
**apply both Linear Regression and Polynomial Regression.**.

* **Objective:**Clean raw datasets, manage feature selection, and apply Python prediction libraries
*             — using both linear and polynomial regression—to generate predictive data.
* **Dataset Used:** Data_Prep_Exercise.csv 
* **Target Variable:** `X = df[['gender', 'Height', 'pre.weight', 'Diet']] 
                        y = df['weight6weeks']`

---

## 🛠️ Tech Stack & Python Libraries Used
- **Data Manipulation:** `pandas`, `numpy`
- **Exploratory Data Analysis (EDA) & Visualization:** `matplotlib`, `seaborn`
- **Predictive Modeling & Scikit-Learn:** `scikit-learn` (Linear regression and Polynomial Regression, Train/Test Split, Metrics)
- **Data Preprocessing:** `StandardScaler`, `OneHotEncoder`

---

## 📂 Repository Structure
```text
├── Data/
│   ├── Data_Prep_Exercise.csv           # Original unprocessed dataset
│   └── Data_Prep_Exercise_Lab2.csv      # Dataset after pipeline processing
├── Notebooks/
│   └── Lab_2_Task_2.ipynb               # Complete Jupyter Notebook with code and comments
├── README.md                            # Project documentation
└── requirements.txt                     # Required Python packages
```

---

## ⚙️ Data Engineering & Modeling Workflow

### 1. Data Cleaning & Transformation
- **Handling Missing Values:** Applied statistical imputation methods to preserve dataset utility without introducing bias.


### 2. Exploratory Data Analysis (EDA)
- Generated distribution plots and correlation matrices using `seaborn` to understand relationships between key business variables.


### 3. Predictive Modeling & Evaluation
- Split data into training and testing sets (80/20 split) to ensure robust model validation.
- Trained predictive classifiers  to Linear Regression and Polynomial Regression.


### MODEL PERFORMANCE COMPARISON 
- Linear Regression  -> R²:  0.9742 | MSE:  3.1586
- Polynomial (Deg 2) -> R²: -0.9681 | MSE: 240.9081


---
📧 **Contact:** Johanna.oleo@gmail.com | [LinkedIn](https://linkedin.com)
