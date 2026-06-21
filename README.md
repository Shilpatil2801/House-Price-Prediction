# House Price Prediction using Machine Learning

## Project Overview

This project develops a machine learning model to predict house prices based on various property features. The workflow includes data preprocessing, feature engineering, model training, performance evaluation, and visualization. Two regression algorithms—Linear Regression and Random Forest Regression—are implemented and compared to determine the better-performing model.

---

## Dataset

The project uses the **Housing.csv** dataset, which contains information about residential properties, including:

- Price (target variable)
- Area
- Number of bedrooms
- Number of bathrooms
- Number of stories
- Parking spaces
- Main road access
- Guest room availability
- Basement
- Hot water heating
- Air conditioning
- Preferred area
- Furnishing status

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature encoding using One-Hot Encoding
- Linear Regression model
- Random Forest Regression model
- Model performance evaluation
- Data visualization using Matplotlib and Seaborn

---

## Project Workflow

### 1. Data Loading
- Import the housing dataset into a Pandas DataFrame.
- Explore the dataset structure and summary statistics.

### 2. Data Preprocessing
- Check for missing values.
- Remove duplicate records.
- Convert categorical variables into numerical format using One-Hot Encoding.

### 3. Exploratory Data Analysis
- Visualize the distribution of house prices.
- Generate a correlation heatmap.
- Analyze relationships between important features and the target variable.

### 4. Model Training

The dataset is split into training and testing sets using an **80:20 ratio**.

The following machine learning models are trained:

- Linear Regression
- Random Forest Regression

### 5. Model Evaluation

The models are evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

The evaluation metrics are compared to determine the best-performing model.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub
- Jupyter Notebook/Google Colab

---

## Project Structure

```
House-Price-Prediction/
│
├── house_price_prediction.ipynb
├── Housing.csv
├── README.md
└── Charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── feature_relationships.png
```

---

## Results

The project compares the performance of Linear Regression and Random Forest Regression for predicting house prices.

The analysis shows that important factors affecting house prices include:

- House area
- Number of bathrooms
- Number of stories
- Air conditioning
- Preferred area

The model evaluation metrics help determine which regression model performs better on the dataset.

---

## Future Improvements

Possible enhancements include:

- Hyperparameter tuning for Random Forest
- Cross-validation for improved model reliability
- Feature selection techniques
- Testing additional algorithms such as XGBoost, Gradient Boosting, and Support Vector Regression
- Deploying the model as a web application using Flask or Streamlit

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

Navigate to the project directory:

```bash
cd House-Price-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
house_price_prediction.ipynb
```

Run all cells sequentially to reproduce the analysis and model results.

---

## Author

**House Price Prediction using Machine Learning**

A machine learning project demonstrating data preprocessing, exploratory data analysis, regression modeling, model comparison, and visualization using Python.