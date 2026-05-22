# Student Performance Prediction using Machine Learning

## Project Overview
This project analyzes student academic performance using Machine Learning techniques. The objective of the project is to predict student performance based on factors such as study time, family background, internet access, absences, and other academic-related attributes.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Train-Test Split
6. Random Forest Model Building
7. Model Evaluation

## Data Preprocessing
- Checked missing values and duplicate records
- Created a target column for student result prediction
- Removed grade-related columns to avoid data leakage
- Encoded categorical variables using pd.get_dummies()

## Exploratory Data Analysis
The project analyzed:
- Study time and student performance
- Impact of absences on final results
- Family and educational background factors
- Student behavior patterns affecting academic performance

## Machine Learning Model
Random Forest Classifier was used to predict student performance.

## Model Evaluation
The model was evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

## Key Insights
- Students with higher study time showed better performance
- Higher absence rates negatively affected academic results
- Educational and family support factors influenced student outcomes

## Conclusion
This project demonstrates how machine learning techniques can be applied to predict student performance and identify important factors affecting academic success.
