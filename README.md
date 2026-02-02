# Position_Salaries
 Project Overview This project demonstrates how regression techniques can be used in **HR Analytics** to predict employee salaries based on job level.  The HR team of a company uses a **Level vs Salary structure** to decide compensation.   However, salary growth across levels is **non-linear**, especially at senior positions.
Business Problem
An employee has applied for the role of **Regional Manager** and already has **2 years of experience** in the same role.

- Regional Manager falls between **Level 6 and Level 7**
- Final assumed level = **6.5**

📌 **Objective:**  
Predict the **salary** that should be offered to the employee using regression models.

---

## 📊 Dataset Description
The dataset contains job levels and corresponding salaries used by HR.


## 🧠 Machine Learning Life Cycle Followed
1. Business Understanding  
2. Data Understanding  
3. Exploratory Data Analysis (EDA)  
4. Model Building  
5. Model Evaluation  
6. Model Comparison  
7. Final Prediction  
8. Business Recommendation  

---

## 🔹 Models Implemented

### 1️⃣ Linear Regression
- Assumes a straight-line relationship between Level and Salary
- Used as a **baseline model**
- Fails to capture non-linear salary growth

### 2️⃣ Polynomial Regression
- Captures the curved relationship between Level and Salary
- Provides a better fit for senior-level salaries
- Produces more accurate predictions

---

## 📈 Model Evaluation & Diagnostics
The following diagnostics were used:
- The models were evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Visual comparison of regression curves

📌 **Result:**  
Polynomial Regression outperforms Linear Regression in terms of accuracy and fit.

---

## 🎯 Final Prediction
- **Input Level:** 6.5
- **Recommended Model:** Polynomial Regression
- **Outcome:** Fair and data-driven salary estimation


---

## 📊 Tools & Technologies Used
- **Python**
- **Scikit-learn**
- **Matplotlib**
- **Pandas**
- **Excel**
- **Jupyter Notebook (exported as HTML)**
