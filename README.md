
# **Time Series Prediction using Machine Learning (TpML)**

## **Overview**

This project explores Time Series forecasting using various Machine Learning techniques. It covers data preprocessing, visualization, feature engineering, model training, and performance evaluation — all inside a Jupyter Notebook.

##  **Features**

- **Load and Explore Data:** Imports time series data and performs initial exploration.
- **Data Preprocessing:** Handles missing values, scales features, and prepares data for modeling.
- **Feature Engineering:** Extracts time-based features (e.g., day, month, year) to enrich the dataset.
- **Modeling:** Implements Machine Learning models like Decision Trees, Random Forest, Gradient Boosting, and more.
- **Performance Evaluation:** Uses metrics like Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R² score.

## 🚀 **Setup Instructions**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-repo/TpML.git
   cd TpML
   ```

2. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook TpML.ipynb
   ```

## **Data Requirements**

Ensure your time series dataset is in a CSV or similar format with a clear datetime index column.

## **Models Covered**

- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Linear Regression
- Support Vector Regression (optional, if implemented)

## **Performance Metrics**

The notebook evaluates model performance using:

- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Square Error)
- **R² score** (Coefficient of determination)

##  **Future Improvements**

- Implementing advanced models like LSTM or Prophet.
- Hyperparameter tuning with GridSearch or RandomSearch.
- Adding cross-validation for more reliable performance analysis.

