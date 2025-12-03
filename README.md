# Student Performance Prediction – README

This project analyzes student performance data and builds various machine learning regression models to predict the **Performance Index** based on multiple academic and personal factors.

---

## 📌 **Project Overview**

This notebook performs complete end‑to‑end data analysis and regression modeling using Python. It includes:

* Data loading and inspection
* Exploratory data analysis (EDA)
* Visualization
* Outlier detection
* Feature scaling and encoding
* Train/validation/test splits
* PCA transformation
* Multiple regression algorithms
* Evaluation using MSE
* Visualization of predictions

---

## 📁 **Dataset**

The dataset used:

```
Student_Performance.csv
```

It includes various features such as:

* Hours Studied
* Previous Scores
* Attendance
* Sleep Hours
* Extracurricular Activities
* ...and more

The target variable is:

* **Performance Index**

---

## 🚀 **Workflow Summary**

### 1. **Import Necessary Libraries**

The project uses libraries like NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn, and XGBoost.

### 2. **Load and Inspect Data**

* Display shape, head, and info
* Check for missing values

### 3. **Visualizations & EDA**

* Box plots for outlier detection
* Histograms for distribution
* KDE plots
* Pie chart for categorical distribution
* Pairplots for feature interaction
* Correlation heatmap

### 4. **Data Cleaning**

* Remove duplicates
* Handle numerical scaling with MinMaxScaler
* Label encode categorical features

### 5. **Train / Validation / Test Split**

* 70% training
* 30% temporary → split into validation and test (70/30)

### 6. **PCA Transformation**

Principal Component Analysis is applied to validation and test sets.

### 7. **Regression Models Used**

The notebook trains and evaluates:

* **Linear Regression**
* **Support Vector Regressor (SVR)**
* **K-Nearest Neighbors (KNN) Regressor**
* **Random Forest Regressor**
* **Gradient Boosting Regressor**
* **XGBoost Regressor**

Each model outputs:

* Validation MSE
* Test MSE
* Prediction vs Actual comparison table
* Scatter plot of predicted vs actual values

### 8. **Model Evaluation Metrics**

* **Mean Squared Error (MSE)**
* Visualization of predictions

A helper function (`plot_predicted_vs_actual_seaborn`) is included to show model performance.

---

## 📊 **Visualization**

Several plots are included to understand:

* Feature distribution
* Outliers
* Relationships between variables
* Model prediction accuracy
* Correlation heatmap

---

## 🧠 **Goal of the Project**

To identify:

* Which factors impact student performance
* Which regression model provides the best prediction accuracy

---

## ⚙️ **Technologies Used**

* **Python 3**
* **NumPy, Pandas** – Data handling
* **Matplotlib, Seaborn** – Visualization
* **Scikit-Learn** – ML models & preprocessing
* **XGBoost** – Gradient boosting model

---

## 📈 **Expected Outcomes**

* A clear comparison of multiple regression models
* Visual insights into student behavior and its influence on performance
* Clean and preprocessed dataset ready for model training

---

## 📦 **How to Run the Notebook**

1. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
   ```
2. Download the dataset into the working directory.
3. Run all notebook cells sequentially.

---

## 📝 **Author**

This project was created as part of a machine learning study and demonstrates full model development workflow.

---

If you need help improving the notebook, optimizing models, or creating visual summaries, feel free to ask!
