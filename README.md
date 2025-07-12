# 💼 Salary Prediction Project

This project focuses on predicting employee salaries using machine learning techniques based on a variety of features such as education level, years of experience, job title, industry, location, and more. It aims to assist organizations in making informed salary decisions and understanding compensation patterns within their workforce.

---

## 🔍 Project Overview

Accurately predicting salaries helps companies optimize compensation strategies and ensures competitiveness in the job market. By leveraging historical salary data and employee attributes, this project builds a model that can estimate expected salaries for new or existing employees.

---


---

## ⚙️ Model Building

- **Algorithm:** Random Forest Regressor
- **Parameters:** 50 decision trees (`n_estimators=50`), fixed `random_state` for reproducibility.
- **Training:** Data split into 80% training and 20% validation.
- **Evaluation Metric:** Root Mean Squared Error (RMSE) calculated on validation data to quantify prediction accuracy.

---


---

## 🧑‍💻 How to Run the Project

1. Clone the repository or download the source files.
2. Ensure you have the required Python libraries installed:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
