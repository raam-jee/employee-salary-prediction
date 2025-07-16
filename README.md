# 💼 Employee Salary Prediction Using ML & DL

This capstone project aims to predict employee salaries using both Machine Learning (ML) and Deep Learning (DL) techniques. By analyzing features such as experience, education, job role, location, and skills, the system builds models that offer accurate salary estimates and helps demonstrate practical AI implementation.

---

## 🎯 Project Objectives
- Perform exploratory data analysis (EDA) on employee datasets
- Build predictive ML models (Linear Regression, Random Forest, XGBoost)
- Design a deep learning model using TensorFlow/Keras
- Evaluate models using MAE, RMSE, and R² Score
- Deploy the final model using Streamlit for interactive use

---

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, TensorFlow, Streamlit  
- **Tools:** Jupyter Notebook, GitHub, Heroku/Render (optional)

---

## 🗂️ Project Structure

---

## 📊 Results and Screenshots

### 🔹 Salary Distribution  
![Salary Distribution](results/salary_distribution.png)

### 🔹 Feature Correlation  
![Correlation Heatmap](results/feature_correlation.png)

### 🔹 ML Model Performance  
![ML Scores](results/ml_model_scores.png)

### 🔹 DL Training Loss  
![DL Loss Curve](results/dl_loss_curve.png)

### 🔹 Streamlit Web App Interface  
![Streamlit UI](results/streamlit_ui.png)

---

## 💻 How to Run Locally

```bash
git clone https://github.com/raam-jee/employee-salary-prediction.git
cd employee-salary-prediction
pip install -r requirements.txt
streamlit run streamlit_app/app.py

