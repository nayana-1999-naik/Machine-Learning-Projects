# Car Insurance Modelling using Python

## 📘 Project Overview

This project aims to develop a machine learning model to predict the number of insurance claims based on various factors such as the driver's age, car age, and region. The dataset used for this analysis is `insurance_claims.csv`, which contains historical data on insurance claims.

## 📊 Dataset Description

The dataset comprises the following columns:

- **age_of_driver**: Age of the driver (numeric)
- **car_age**: Age of the car (numeric)
- **region**: Geographical region (categorical: Urban, Suburban, Rural)
- **number_of_claims**: Number of insurance claims made (numeric)

## 🔧 Technologies Used

- **Python**: Programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms and preprocessing

## 📂 Project Structure

Car-Insurance-Modelling/
│
├── insurance_claims.csv # Dataset
├── Car_Insurance_Modelling.ipynb # Jupyter notebook for analysis
└── README.md # Project documentation


## 🧪 Analysis Workflow

1. **Data Loading**: Import the dataset using Pandas.
2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of numerical features.
   - Analyze the correlation between features.
   - Examine the distribution of categorical variables.
3. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Split the dataset into training and testing sets.
4. **Model Building**:
   - Train machine learning models (e.g., Linear Regression, Decision Trees).
   - Evaluate model performance using appropriate metrics.
5. **Model Evaluation**:
   - Assess the model's accuracy and make necessary improvements.
