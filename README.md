# 📏 Weight to Height Prediction using Linear Regression

This project uses **Linear Regression** to predict a person’s **height (dependent variable)** based on their **weight (independent variable)**.  
It demonstrates how a machine learning model can learn real-world trends from scattered data and make numerical predictions.

---

## 🧠 Objective

To build a machine learning model that predicts **height** using **weight** as the input feature.

---

## 📊 Dataset

The dataset contains two columns:

- **Weight (kg)** → Independent variable  
- **Height (cm)** → Dependent variable  

The data is intentionally **scattered (noisy)** to reflect real-world variation rather than a perfect straight line.

---

## 🔧 Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  

---

## ⚙️ Model Workflow

1. Load weight–height dataset  
2. Visualize data using a scatter plot  
3. Split data into training and testing sets  
4. Train a Linear Regression model  
5. Predict height from weight  
6. Evaluate model using R² and Adjusted R²  
7. Plot regression line  

---

## 📈 Model Performance

| Metric | Value |
|------|-------|
| R² Score | 0.7769 |
| Adjusted R² | 0.7026 |

### Interpretation

- About **77% of the variation in height** is explained by weight  
- Adjusted R² confirms the model is statistically reliable  
- The scatter represents natural variation in human body measurements  

---

## 📌 Conclusion

The model successfully learns the relationship between weight and height.  
Using weight as input, it can predict height with a strong degree of accuracy in terms of explained variance, making it useful for trend analysis and approximate predictions.

---

## 🚀 How to Run

Install required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
