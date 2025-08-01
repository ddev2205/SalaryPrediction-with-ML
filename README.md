# SalaryPrediction with ML

Welcome to **SalaryPrediction with ML**!  
This is a machine learning project created as part of my beginner journey during the virtual PBEL IBM Internship. The project aims to predict employee salaries based on various features using multiple regression models.

## Project Overview

In today's rapidly evolving job market, understanding factors influencing salary can be highly valuable for both job seekers and employers. This project predicts salaries based on attributes such as:

- **Age**
- **Gender**
- **Education Level**
- **Job Title**
- **Years of Experience**

The dataset includes 375 records with 6 features, providing a real-world context for learning and experimentation.

## Main Steps

1. **Data Loading & Exploration**
    - Loaded a CSV dataset with features mentioned above.
    - Explored the data, checked for missing values, and analyzed correlations.

2. **Data Preprocessing**
    - Encoded categorical values like Gender, Education Level, and Job Title using Label Encoding.
    - Performed normalization/scaling where appropriate.

3. **Model Selection**  
    Trained and evaluated three regression models:
    - **Linear Regression**
    - **Decision Tree Regressor**
    - **XGBoost Regressor**

4. **Model Evaluation**
    - Used metrics including R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE) for performance assessment.

5. **Results & Insights**
    - Analyzed which features contribute most to salary prediction.
    - Compared model performances using derived metrics and plots.

## Results (Sample Output)

- **Highest Correlation to Salary:** Years of Experience (0.92) and Age (0.91)
- **Important Features:** Besides direct years of experience, education level also shows a moderate influence.

## How to Run

1. Clone this repository or download the notebook:
    ```
    git clone https://github.com/ddev2205/SalaryPrediction-with-ML
    ```
2. Install required libraries:
    ```
    pip install pandas scikit-learn xgboost matplotlib seaborn
    ```
3. Open and run `employe-salary-prediction-using-ml.ipynb` in Jupyter or Colab.

## Key Skills Practiced

- Data preprocessing (encoding, normalization)
- Exploratory Data Analysis (EDA)
- Model implementation and evaluation
- Visualization of correlations and results

## Acknowledgements

This project was completed as a **beginner** during the virtual PBEL IBM Internship. All insights and code are part of my personal learning and development journey.

Thank you for checking out my project! If you're also learning, feel free to fork, modify, or ask questions.
