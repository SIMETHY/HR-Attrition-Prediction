# 🧑‍💼 HR Attrition Prediction using Machine Learning

## 📌 Project Overview
Employee attrition is a major challenge for organizations, leading to productivity loss and increased hiring costs. This project builds a **Machine Learning classification model** to predict whether an employee will leave the company.

The model uses features like:
- Age  
- Salary  
- Job Role  
- Job Satisfaction  
- Work Experience  
- Work-Life Balance  
- Department  

---

## 🎯 Objective
- Analyze the HR dataset  
- Perform data preprocessing  
- Build multiple ML models  
- Evaluate performance  
- Identify the best model  

---

## 📊 Dataset Description
The dataset includes:
- Demographics (Age, Gender, Marital Status)  
- Job-related info (Department, Role, Salary)  
- Performance metrics (Job Satisfaction, Environment Satisfaction)  
- Work metrics (Years at Company, Work-Life Balance)  

**Target Variable:**
- Attrition (Yes/No)

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  
- Outlier handling  

### 2. Exploratory Data Analysis (EDA)
- Univariate analysis  
- Bivariate analysis  
- Correlation heatmap  

### 3. Feature Engineering
- Feature selection  
- Transformations (log, scaling)  

### 4. Model Building
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Gradient Boosting  

### 5. Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 📈 Key Insights
- Low job satisfaction → higher attrition  
- Overtime → strong impact on attrition  
- Lower income employees leave more  
- Early-career employees have higher attrition  
- Certain roles (e.g., Sales) show higher churn  

---

## 🏆 Results
- Logistic Regression provided a strong baseline  
- Tree-based models improved performance  
- Balanced precision and recall achieved  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/SIMETHY/HR-Attrition-Prediction.git

# Go to project folder
cd HR-Attrition-Prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
