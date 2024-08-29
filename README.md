# Road Traffic Accident Analysis and Prediction

## Overview
This project aims to analyze road traffic accidents in the UK, focusing on identifying the factors that contribute to the severity of accidents and predicting severe accidents using machine learning models. The project includes data preprocessing, exploratory data analysis, spatial analysis, and the application of various machine learning techniques.

## Features
- **Data Loading and Preprocessing:** Load and preprocess the dataset from the UK Department of Transport, including casualty, collision, and vehicle data.
- **Exploratory Data Analysis (EDA):** Analyze the impact of speed limits, weather conditions, temporal trends, and geographic distribution on accident severity.
- **Spatial Analysis:** Identify accident hotspots using geographic data and heatmaps.
- **Junction Control Analysis:** Evaluate the effectiveness of different junction control methods in preventing severe accidents.
- **Machine Learning Models:** Apply and compare several models, including K-Nearest Neighbors (KNN), Logistic Regression, Decision Tree, and Random Forest, to predict the severity of accidents.

## Data
The dataset used in this project is sourced from the UK Department of Transport's road safety open data. It includes detailed records of accidents, vehicles involved, and casualties. The data is structured in three main files: casualty data, collision data, and vehicle data.

## Usage
1. **Data Preparation:**
   - Load the dataset files.
   - Merge the datasets on the accident index.
   - Perform feature selection and encoding.
   - Apply SMOTE to handle class imbalance in the target variable.

2. **Exploratory Data Analysis:**
   - Analyze the distribution of accidents based on speed limits, weather conditions, and temporal trends.
   - Visualize geographic accident hotspots and severe accident rates by region.

3. **Machine Learning Modeling:**
   - Apply machine learning models (KNN, Logistic Regression, Decision Tree, Random Forest) to predict severe accidents.
   - Evaluate the performance of each model using accuracy, precision, recall, F1 score, and confusion matrix.

4. **Results Interpretation:**
   - Summarize and interpret the findings from the EDA and machine learning models.
   - Identify key factors contributing to severe accidents and provide insights for road safety improvements.


## Results
- The Decision Tree model achieved the highest accuracy at 76%, followed by the Random Forest model with 74.95%.
- Speed limits, weather conditions, and junction control types were identified as significant factors influencing accident severity.
- Spatial analysis revealed regional hotspots with high rates of severe accidents, suggesting areas for targeted interventions.

## Limitations
- The study is limited to data from the UK and may not be generalizable to other regions.
- The analysis does not focus on driver-related factors, which are significant contributors to accidents.
- Further exploration of other machine learning models could enhance predictive accuracy.

## Future Work
- Extend the analysis to include driver behavior and other human factors.
- Explore additional machine learning models and techniques.
- Apply the findings to develop real-time predictive systems for accident prevention.
