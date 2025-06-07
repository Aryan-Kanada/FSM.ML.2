#  Medical Cost Prediction using Linear Regression

This project implements **Linear Regression from scratch** using only `NumPy`, `Pandas`, and `Matplotlib` to predict medical insurance costs. The dataset includes demographic and lifestyle features like age, BMI, smoking habits, and region. The goal is to understand how these factors affect insurance charges.

---

## Dataset
  - `age`: Age of the individual
  - `sex`: Gender (`male`, `female`)
  - `bmi`: Body Mass Index
  - `children`: Number of children covered by insurance
  - `smoker`: Whether the person smokes
  - `region`: Residential area in the US
  - `charges`: Medical insurance charges (Target)

---

## Project Highlights

### 1.  Data Exploration
- Displayed summary statistics and null values
- Visualized key features using histograms, scatterplots, and countplots

### 2.  Preprocessing
- Categorical encoding (`sex`, `smoker`, `region`)
- Feature scaling (min-max normalization)
- Bias term added manually
- Train-test split implemented manually (no `sklearn`)

### 3.  Linear Regression from Scratch
- Implemented gradient descent using NumPy
- Manually computed:
  - Mean Squared Error (MSE)
  - R² Score
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)

### 4.  Evaluation & Visualization
- Training loss curve
- Actual vs predicted values plot
- Residual analysis
- Feature importance (based on coefficients)

---

##  Model Performance

| Metric                | Value         |
|-----------------------|---------------|
| R² Score (Train)      | ~0.74+        |
| R² Score (Test)       | ~0.73+        |
| MAE                   | ~$2700±       |
| RMSE                  | ~$5000±       |

*Note: Actual values may vary slightly based on the random split.*

---

## 🛠️ Technologies Used
- `Python`
- `NumPy`
- `Pandas`
- `Matplotlib`
- `Seaborn`

---



