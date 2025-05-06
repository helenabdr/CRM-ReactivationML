# CRM-Reactivation

**Goal:**  
Develop a machine learning model to identify clients with the highest propensity to be reactivated after a 2-year period without any purchases.

---

## 📊 Project Description

This project focuses on customer reactivation within a CRM (Customer Relationship Management) system. Using historical purchase data and client registry information, the objective is to build a predictive model that identifies customers most likely to return after a long period of inactivity (specifically, 2 years with no purchases).

---

## 🗂️ Available Data

1. **Clients’ Purchase History (5 years)**
   - `SALES`
   - Purchase details: date, value, item type, etc.

2. **Clients Registry**
   - `CLIENT`
   - Demographics & profile: registration date, residence location, sector, risk category, etc.

---

## 📈 Expected Results

A predictive model that estimates the **propensity to reactivate** for each inactive client. The model helps target the most promising clients for re-engagement campaigns.

---

## 📁 Repository Contents

- `data_preparation.ipynb`  
  Exploratory data analysis and preprocessing steps, including cleaning, feature engineering, and data exploration.

- `ml_modeling.ipynb`  
  Model training, evaluation, and selection to predict reactivation likelihood.

---

## 🚀 How to Use

1. Clone the repository.
2. Run the notebooks in order using Jupyter or any compatible environment.
3. Modify input paths and parameters if needed.

---

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook
- Common libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, etc.