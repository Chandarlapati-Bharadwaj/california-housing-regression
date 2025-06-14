# 🏠 California Housing Price Prediction

## 📌 Overview

This project aims to predict California housing prices using two regression techniques:  
- **Linear Regression** (for simplicity and interpretability)  
- **Random Forest Regressor** (for higher accuracy and non-linear pattern detection)

Using the **California Housing dataset** from scikit-learn, we explore how different machine learning models perform on a real-world tabular dataset.

---

## 📂 Dataset

- **Source:** scikit-learn’s California Housing dataset  
- **Features:** Median income, house age, average rooms, population, location, etc.  
- **Target Variable:** Median house value (`MedHouseVal`)

---

## 🛠 Tools & Technologies

- Python  
- scikit-learn  
- pandas, numpy  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## ⚙️ Workflow

1. Load and inspect the dataset  
2. Train-Test split (80/20)  
3. Feature scaling using `StandardScaler`  
4. Train and evaluate:
   - Linear Regression
   - Random Forest Regressor  
5. Compare results using MSE and R² score  
6. Visualize feature importance

---

## 🤖 Models Used

### 🔹 Linear Regression
- **Why?**  
  Simple, fast, and easy to interpret. Provides a good baseline model.
- **Limitations:**  
  Assumes linear relationships between features and target. May underperform on complex data.

### 🔸 Random Forest Regressor
- **Why?**  
  Captures non-linear patterns and interactions between features. Generally more accurate.
- **Tradeoff:**  
  Less interpretable than linear models and more computationally intensive.

---

## 📊 Results

| Metric                | Linear Regression | Random Forest Regressor |
|-----------------------|-------------------|--------------------------|
| Mean Squared Error    | 0.5559            | 0.2552                   |
| R² Score              | 0.5758            | 0.8053                   |

> ✅ Random Forest significantly outperforms Linear Regression in both error and variance explained.  
> This demonstrates the importance of trying non-linear models on real-world datasets where relationships between variables may be complex.

---

## 🚀 How to Run

1. Clone this repository  
2. Open the Jupyter Notebook  
3. Run all cells to train both models and visualize results  
4. Adjust hyperparameters or add cross-validation for further experimentation

---

## 🧠 Key Takeaways

- Linear Regression is great for baseline models and interpretability  
- Random Forest significantly improves accuracy by capturing complex relationships  
- Comparing models gives a better understanding of dataset behavior

---
