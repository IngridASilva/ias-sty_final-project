# Car Model | Final Project
## Bachelor's degree in Economics

### Overview

This project builds a **machine learning model** to predict car prices using the CatBoostRegressor algorithm. The dataset is sourced from an Excel file containing car attributes and their respective average **FIPE prices**.

### Features

- Reads car data from an Excel file;
- Processes categorical features for model training;
- Splits data into training and testing sets;
- Utilizes CatBoost for regression modeling;
- Performs hyperparameter tuning using GridSearchCV.

### Virtual Environment Setup

It is **recommended to use a virtual environment** to manage dependencies. Ensure you have **Python 3.12.0** installed, then create and activate a virtual environment:
`python3 -m venv venv` | 
`venv\Scripts\activate    # On Windows`

Then, install the required dependencies:
`pip install -r requirements.txt`

### Requirements

To run this project, install the following dependencies:
`pip install pandas numpy openpyxl scikit-learn catboost matplotlib`

### Running the Model

- Load the dataset from `car_model_fipe.xlsx`;
- Preprocess categorical variables;
- Split data into training and test sets;
- Train CatBoostRegressor;
- Perform hyperparameter tuning;
- Evaluate model performance.

### Usage

Run the script in a Python environment:
`python car_model.py`

Make sure to have the dataset `car_model_fipe.xlsx` in the same directory as the script.

### License

This project is open-source and free to use for educational and research purposes.

