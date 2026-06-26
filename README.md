# Real-Estate-Price-Prediction-From-Scratch
Built Linear Regression from Scratch using NumPy and compared it with Scikit-Learn on a Real Estate Price Prediction dataset.


# 🏡 Real Estate Price Prediction using Linear Regression from Scratch

## 📌 Project Overview

This project demonstrates how **Linear Regression** works by implementing the algorithm completely **from scratch using NumPy**, without relying on machine learning libraries for training.

The objective is to understand the mathematical foundation of Linear Regression, implement **Gradient Descent** manually, and compare the custom implementation with **Scikit-Learn's LinearRegression** model using a real-world Real Estate Price Prediction dataset.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Preprocess the dataset
- Implement Linear Regression from scratch using NumPy
- Train the model using Gradient Descent
- Compare the custom implementation with Scikit-Learn
- Evaluate model performance using multiple regression metrics

---

## 📂 Dataset

- **Dataset:** Real Estate Price Prediction
- **Source:** Kaggle

The dataset contains various property-related features used to predict house prices.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset overview
- Missing value analysis
- Duplicate value check
- Feature distributions
- Correlation analysis
- Outlier detection
- Data visualization

---

## ⚙️ Data Preprocessing

The preprocessing pipeline included:

- Handling missing values
- Feature selection
- Train-Test Split
- Feature Scaling (where required)

---

## 🧠 Linear Regression from Scratch

The model was implemented using only **NumPy**.

Implemented components include:

- Cost Function (Mean Squared Error)
- Gradient Descent Optimization
- Weight Initialization
- Bias Update
- Prediction Function
- Model Training Loop

No machine learning library was used for model training.

---

## 📈 Model Evaluation

The custom NumPy implementation was compared against Scikit-Learn's Linear Regression model.

| Model | MAE | MSE | RMSE | R² Score |
|------|------:|------:|------:|------:|
| Linear Regression (NumPy) | **5.305341** | **53.505457** | **7.314742** | **0.681059** |
| Scikit-Learn Linear Regression | **5.305356** | **53.505619** | **7.314754** | **0.681058** |

---

## 🔍 Key Observation

The NumPy implementation achieved **almost identical performance** to Scikit-Learn's implementation.

This demonstrates that:

- The mathematical implementation is correct.
- Gradient Descent successfully converged.
- Scikit-Learn provides similar predictions while offering optimized performance and faster execution.

---

## 📷 Visualizations

The project includes:

- Correlation Heatmap
- Feature Distribution Plots
- Cost vs Iterations (Gradient Descent Convergence)
- Actual vs Predicted Values
- Residual Analysis

---


## 🚀 Key Learnings

Through this project, I gained a deeper understanding of:

- The mathematics behind Linear Regression
- Gradient Descent optimization
- Model convergence
- Loss Functions (MSE)
- Feature preprocessing
- Model evaluation metrics
- Comparing custom implementations with production-ready libraries

---

## 💡 Future Improvements

- Polynomial Regression
- Regularization (Ridge & Lasso)
- Feature Engineering
- Hyperparameter tuning
- Cross Validation
- Multiple regression algorithms comparison

---

## ⭐ Results

The custom Linear Regression implementation produced nearly identical results to Scikit-Learn, validating the correctness of the algorithm while providing valuable insight into how machine learning models work internally.

---

## 👤 Author

**Kshitija Shejal**

If you found this project helpful, feel free to ⭐ the repository.
