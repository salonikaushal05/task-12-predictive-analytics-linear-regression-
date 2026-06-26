# Task-12-predictive-analytics-linear-regression-
# Task 12: Predictive Analytics using Linear Regression

##  Project Overview

This project was developed as part of the **Data Analytics Internship – Task 12**.

The objective of this project is to build a **Predictive Analytics** model using **Linear Regression** to predict customer **Income** based on various marketing campaign attributes. The project includes data preprocessing, feature engineering, model training, evaluation, prediction, and model saving.


##  Objectives

- Load and explore the marketing campaign dataset
- Perform data preprocessing
- Handle missing values
- Encode categorical variables
- Build a Linear Regression model
- Evaluate model performance
- Make predictions
- Save the trained model

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib


##  Dataset

**Dataset:** Marketing Campaign Dataset

The dataset contains customer demographic information, purchasing behavior, and marketing campaign details used for predictive analytics.


##  Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset
- Explored dataset information
- Checked dataset shape
- Checked duplicate records
- Handled missing values
- Removed unnecessary columns
- Converted date columns into useful features
- Encoded categorical variables using Label Encoding


##  Machine Learning Model

**Algorithm Used:**

- Linear Regression

##  Model Evaluation

The model was evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

| Metric | Value |
|---------|--------|
| MAE | 6730.39 |
| MSE | 96603129.72 |
| RMSE | 9828.69 |
| R² Score | 0.7733 |

The model achieved an **R² Score of 77.33%**, indicating good predictive performance on the marketing dataset.

##  Visualizations

The notebook includes:

- Correlation Matrix
- Actual vs Predicted Scatter Plot
- Residual Plot

These visualizations help understand feature relationships and evaluate model performance.

##  Model Saving

The trained model is saved using **Joblib**.

```python
joblib.dump(model, "linear_regression_model.pkl")
```

##  How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/task-12-predictive-analytics-linear-regression.git
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn openpyxl joblib
```

3. Open the Jupyter Notebook.

4. Run all cells sequentially.

---

## Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Feature engineering
- Label Encoding
- Linear Regression
- Model evaluation
- Predictive Analytics
- Saving machine learning models

---

##  Author

**Saloni Kaushal**

Data Analytics Intern

---

##  Acknowledgement

This project was completed as part of the **Data Analytics Internship Program** to gain practical experience in predictive analytics and machine learning using Python.
