# 📊 Student Performance Prediction using Multiple Linear Regression

## 📌 Project Overview

This project predicts students' exam scores using **Multiple Linear Regression**. The objective is to understand how different academic, personal, and environmental factors influence student performance and to build a regression model capable of predicting exam scores accurately.

The project covers the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation.

---

# 🎯 Objective

To build a Multiple Linear Regression model that predicts students' exam scores based on multiple input features and evaluates the model using standard regression metrics.

---

# 📂 Dataset

**Dataset:** Student Performance Factors Dataset

The dataset contains information related to student performance, including:

- Hours Studied
- Attendance
- Previous Scores
- Sleep Hours
- Teacher Quality
- Parental Involvement
- School Type
- Internet Access
- Extracurricular Activities
- Family Income
- Motivation Level
- Distance from Home
- Peer Influence
- Learning Disabilities
- Tutoring Sessions
- Physical Activity
- Exam Score (Target Variable)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📋 Project Workflow

## 1. Data Loading

- Import dataset
- Inspect dataset structure
- Check data types

---

## 2. Data Preprocessing

- Handle missing values
- Check duplicate records
- Encode categorical variables
- Feature engineering
- Feature scaling using StandardScaler

---

## 3. Exploratory Data Analysis (EDA)

Performed:

- Histograms
- Box Plots
- Count Plots
- Correlation Heatmap
- Pair Plot

---

## 4. Data Preparation

- Feature Selection
- Target Variable Selection
- Train-Test Split (80:20)

---

## 5. Model Building

Algorithm Used:

- Multiple Linear Regression

Training steps:

- Train model
- Generate predictions
- Compare actual vs predicted values

---

## 6. Model Evaluation

Evaluation metrics used:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 7. Model Interpretation

Performed:

- Feature Coefficient Analysis
- Residual Plot
- Actual vs Predicted Plot
- Residual Distribution Analysis

---

# 📈 Model Performance

| Metric | Value |
|---------|------:|
| Mean Absolute Error (MAE) | 0.44 |
| Mean Squared Error (MSE) | 3.24 |
| Root Mean Squared Error (RMSE) | 1.80 |
| R² Score | 0.77 |

---

# 📊 Visualizations

The notebook includes:

- Data Distribution
- Correlation Heatmap
- Feature Importance (Coefficients)
- Residual Plot
- Actual vs Predicted Scatter Plot
- Residual Distribution Histogram

---

# 📁 Repository Structure

```
├── MultiLinearRegression01.ipynb
├── student_performance.csv
├── README.md
```

---

# ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/Student-Performance-Multiple-Linear-Regression.git
```

2. Navigate to the project directory

```bash
cd Student-Performance-Multiple-Linear-Regression
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
MultiLinearRegression01.ipynb
```

Run all cells sequentially.

---

# 📌 Conclusion

The Multiple Linear Regression model successfully predicts students' exam scores with good accuracy. The model achieved an **R² score of 0.77**, indicating that it explains approximately **77%** of the variance in exam scores. The low MAE and RMSE values demonstrate that the predictions are generally close to the actual scores. Diagnostic plots show that the model performs well for most observations, although a small number of high-scoring students are underestimated. Overall, the project provides a strong foundation for understanding regression techniques and the complete machine learning workflow.

---

## 👨‍💻 Author

Vinod G

Machine Learning Enthusiast
