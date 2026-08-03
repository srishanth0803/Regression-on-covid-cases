
# 🦠 Analysis on COVID-19 Cases using Regression Models

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

# 📌 Project Overview

This project analyzes the spread of **COVID-19** using historical case data and applies multiple regression techniques to predict future confirmed cases.

The project begins with exploratory data analysis (EDA) to understand trends in confirmed, recovered, death, active, and closed cases. It then builds and compares different regression models to determine which provides the best prediction accuracy.

---

# 🎯 Objectives

- Analyze COVID-19 case trends over time.
- Perform data preprocessing and feature engineering.
- Visualize the spread of the pandemic.
- Calculate Growth Factor.
- Predict future confirmed cases using regression models.
- Compare model performances using evaluation metrics.

---

# 📂 Dataset

The dataset contains daily COVID-19 statistics including:

- Observation Date
- Province/State
- Country/Region
- Confirmed Cases
- Deaths
- Recovered Cases

The notebook loads the dataset directly from GitHub.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

---

# 📊 Data Analysis

The project performs the following analysis:

- Data Cleaning
- Aggregation of daily COVID statistics
- Total Confirmed Cases
- Total Deaths
- Total Recoveries
- Active Cases Calculation
- Closed Cases Calculation
- Growth Factor Analysis
- Trend Visualization

---

# 📈 Visualizations

The notebook generates several plots including:

- Confirmed Cases vs Time
- Death Cases vs Time
- Recovery Cases vs Time
- Active vs Closed Cases
- Growth Factor of Confirmed Cases
- Growth Factor of Death Cases
- Growth Factor of Recovered Cases
- Actual vs Predicted Cases

---

# 🤖 Machine Learning Models

The following models are implemented:

### 1. Linear Regression

- Baseline prediction model
- Used to predict confirmed COVID-19 cases

### 2. Polynomial Regression

- Degree = 5
- Captures nonlinear growth patterns

### 3. Ridge Regression

- Regularized linear regression
- Hyperparameter tuning using RandomizedSearchCV

### 4. Polynomial Ridge Regression

- Polynomial Features + Ridge Regression
- Provides the best prediction performance among all models

---

# 📏 Model Evaluation

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

After comparing all models, **Polynomial Ridge Regression** achieved the best performance with the lowest prediction error.

---

# 📁 Project Structure

```
Analysis_on_COVID_Cases.ipynb
README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Analysis-on-COVID-Cases.git
```

Move into the project directory

```bash
cd Analysis-on-COVID-Cases
```

Install dependencies

```bash
pip install pandas numpy matplotlib scipy scikit-learn
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Analysis_on_COVID_Cases.ipynb
```

---

# 📌 Key Learning Outcomes

- Data preprocessing using Pandas
- Feature engineering
- Exploratory Data Analysis
- Growth Factor computation
- Regression techniques
- Polynomial Feature Engineering
- Ridge Regularization
- Hyperparameter tuning
- Model evaluation and comparison
- Data visualization using Matplotlib

---

# 📸 Sample Workflow

```
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
EDA & Visualization
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Linear Regression
      │
      ▼
Polynomial Regression
      │
      ▼
Ridge Regression
      │
      ▼
Polynomial Ridge Regression
      │
      ▼
Model Evaluation
```

---

# 📈 Future Improvements

- Predict deaths and recoveries separately.
- Forecast future cases using time-series models.
- Implement ARIMA and Prophet models.
- Apply LSTM neural networks.
- Build an interactive dashboard using Streamlit.

---

# 👨‍💻 Author

**Gottam Srishanth**

- Python Developer
- Machine Learning Enthusiast
- Data Analytics Learner

---

## ⭐ If you found this project helpful, don't forget to star the repository!
