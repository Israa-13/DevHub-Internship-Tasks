# DevHub-Internship-Tasks
DevelopersHub Corporation AI/ML Internship Tasks.

# Task 1 — Iris Dataset Exploration & Visualization
**Notebook:** `Task1_Iris_Exploration.ipynb`

### **Overview**
This task explores the classic Iris dataset to understand:
- Feature distributions  
- Species differences  
- Correlations  
- Visual relationships via pairplots, boxplots, and histograms  

### **Key Insights**
- Petal length and petal width strongly differentiate species.  
- *Setosa* is linearly separable from *Versicolor* and *Virginica*.  
- Correlation matrix shows strong coupling between petal measurements.  

---

# Task 2 — Stock Price Prediction (Regression)

**Notebook:** `Task2_Stock_Prediction.ipynb`

### **Overview**
This task predicts stock **Closing Price** using features such as:
- Open  
- High  
- Low  
- Volume  
- Previous Close  

Models included:
- Linear Regression  
- Random Forest Regressor  

### **Key Insights**
- Random Forest captures non-linear patterns and typically performs better.  
- Linear Regression works but struggles with volatile markets.  
- Adding technical indicators (moving averages, RSI, MACD) greatly improves results.  

---

# Task 3 — Heart Disease Prediction (Classification)

**Notebook:** `Task3_Heart_Disease_Prediction.ipynb`

### **Overview**
Using the UCI Heart Disease dataset, this task builds and evaluates:
- Logistic Regression  
- Decision Tree Classifier  

Metrics include:
- Accuracy  
- Confusion Matrix  
- ROC Curve / AUC  
- Feature Importance  

### **Key Insights**
- Logistic Regression provides stable, interpretable predictions.  
- Important predictors often include:  
  - Chest pain type  
  - Maximum heart rate  
  - ST depression (oldpeak)  
- ROC-AUC highlights model separation ability, crucial for medical datasets.  
