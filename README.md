# 🏥 Health Insurance Cost Analysis & Regression Modeling  

A project to analyze factors affecting **health insurance costs** and build **regression models** to predict insurance charges.  

---

## 📋 Table of Contents  
1. [Project Overview](#-project-overview)  
2. [Dataset](#-dataset)  
3. [Features](#-features)  
4. [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  
5. [Modeling](#-modeling)  
6. [Evaluation Metrics](#-evaluation-metrics)  
7. [Results](#-results)  


---

## 🧐 Project Overview  
This project analyzes a **health insurance dataset** to understand which factors influence insurance costs and builds regression models to predict insurance charges.  

The goal is:  
- 🔍 Explore trends and relationships in the data  
- 🤖 Build predictive models  
- 📊 Evaluate model performance  
- 💡 Derive actionable insights  

---

## 📂 Dataset  
The data comes from a **public Kaggle dataset**, containing individual-level health insurance data.  

**Key fields include:**  
- `age` – Age of the individual  
- `sex` – Gender (male / female)  
- `bmi` – Body Mass Index  
- `children` – Number of children  
- `smoker` – Smoker or non-smoker  
- `region` – Geographic region  
- `charges` – Insurance cost *(Target Variable)*  

---

## 🔍 Features  

| Feature   | Description |
|-----------|-------------|
| **age**   | Age of the individual |
| **sex**   | Gender (male / female) |
| **bmi**   | Body Mass Index |
| **children** | Number of children the individual has |
| **smoker** | Smoker or non-smoker |
| **region** | Geographic region |
| **charges** | Insurance cost (Target variable) |

---

## 📈 Exploratory Data Analysis (EDA)  
- 📊 Investigating distributions of continuous features (`age`, `bmi`, `children`)  
- 🔗 Checking for correlations between variables  
- 🌍 Visualizing differences in charges by `smoker` status, `region`, etc.  
- 🛠 Handling categorical variables via encoding  
- ⚠️ Checking for outliers and missing values  

---

## 🤖 Modeling  
Steps followed for building predictive models:  
1. 📂 Splitting data into **training** and **test sets**  
2. 🔨 Using regression algorithms (Linear Regression, Ridge, Lasso, ElasticNet, etc.)  
3. 🧩 Feature engineering & preprocessing (encoding categorical variables, scaling if needed)  
4. ⚙️ Hyperparameter tuning *(if implemented)*  

---

## 📊 Evaluation Metrics  
The following metrics were used to evaluate model performance:  
- 📉 **RMSE** – Root Mean Squared Error  
- 📏 **MAE** – Mean Absolute Error  
- 📈 **R²** – Coefficient of Determination  

---

## 🏆 Results  
- ✅ Summary of which model performed best  
- 📊 Comparison of predictions vs actual insurance charges  
- 💡 Key insights (e.g., **smoker status has the largest impact on cost**)  
