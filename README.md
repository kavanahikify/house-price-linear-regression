# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project uses a simple Linear Regression model to predict house prices based on key features such as living area, number of bedrooms, and number of bathrooms. It is a beginner-friendly machine learning project focused on understanding the end-to-end workflow.

---

## 📂 Dataset

The dataset consists of:

* `train.csv` → Used to train the model
* `test.csv` → Used to generate predictions

### Features Used:

* `GrLivArea` → Above ground living area (square feet)
* `BedroomAbvGr` → Number of bedrooms
* `FullBath` → Number of full bathrooms

### Target:

* `SalePrice` → Price of the house

---

## ⚙️ Steps Performed

1. Data loading and cleaning
2. Feature selection
3. Handling missing values using median
4. Splitting data into training and validation sets
5. Training a Linear Regression model
6. Model evaluation using RMSE
7. Visualization of Actual vs Predicted prices
8. Generating predictions on test data

---

## 📊 Model Performance

* Metric used: Root Mean Squared Error (RMSE)
* Lower RMSE indicates better model performance

---

## 📈 Visualization

A scatter plot is used to compare actual vs predicted house prices along with a reference line for perfect predictions.

---

## 📁 Output

* `submission.csv` → Contains predicted house prices for test data

---

## 🚀 How to Run

1. Install required libraries:

   ```bash
   pip install pandas matplotlib scikit-learn
   ```

2. Run the script:

   ```bash
   python your_script_name.py
   ```

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## 📌 Future Improvements

* Add more features for better accuracy
* Try advanced models (Random Forest, XGBoost)
* Perform feature engineering
* Hyperparameter tuning

---

## 👨‍💻 Author

Your Name

---

## ⭐ Acknowledgment

This project is inspired by beginner-level machine learning tasks for understanding regression models.
