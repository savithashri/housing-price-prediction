# 🏠 Housing Price Prediction

## 📌 Overview
Housing prices depend on multiple factors such as location, number of rooms, population density, and income levels.  
This project demonstrates how to build a **machine learning pipeline** to predict housing prices 

The notebook covers:
- **Exploratory Data Analysis (EDA):** Understanding features, distributions, and correlations.  
- **Data Preprocessing:** Handling missing values, scaling, and encoding categorical variables.  
- **Model Training:** Applying regression techniques to predict housing prices.  
- **Evaluation & Visualization:** Measuring performance with metrics and visualizing predictions vs actual values.  

This project is designed for **students, researchers, and practitioners** who want a clear, step-by-step example of applying machine learning to a real-world dataset.

---

## 🛠 Tools & Libraries Used
- **Python 3**  
- **Google Colab / Jupyter Notebook**  
- **Libraries:**
  - `pandas` → Data manipulation  
  - `numpy` → Numerical computations  
  - `matplotlib` & `seaborn` → Visualization  
  - `scikit-learn` → Machine learning models and metrics  

---

## ⚙️ Methods to Train the Data
1. **Data Splitting:**  
   - Train-Test split using `train_test_split` (80% training, 20% testing).  

2. **Model Selection:**  
   - Linear Regression (baseline model).  
   - Other regression models can be added (Decision Tree, Random Forest, etc.).  

3. **Training Process:**  
   - Fit the model on training data (`model.fit(X_train, y_train)`).  
   - Predict on test data (`model.predict(X_test)`).  

4. **Evaluation Metrics:**  
   - Root Mean Squared Error (RMSE).  
   - R² Score (coefficient of determination).  

5. **Visualization:**  
   - Scatter plot of Actual vs Predicted prices.  
   - Residual plots to check errors.  

---

## 📊 Dataset
- **Source:** California Housing dataset from kaggle  
- **Features:**
  - Median income  
  - House age  
  - Average rooms per household  
  - Average bedrooms per household  
  - Population  
  - Latitude & Longitude  
- **Target:** Median house value (`price`).  


---
