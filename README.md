Framingham Heart Disease Prediction

Overview

The Framingham Heart Disease Prediction project is a Machine Learning application that predicts the risk of developing coronary heart disease (CHD) within the next 10 years using the Framingham Heart Study dataset. The model analyzes various health and lifestyle factors to provide a prediction that can assist in early risk assessment.

Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature selection
- Machine Learning model training
- Model evaluation using performance metrics
- Predicts 10-year risk of heart disease

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

Dataset

The project uses the Framingham Heart Study dataset, which includes attributes such as:

- Age
- Gender
- Education
- Smoking status
- Cigarettes per day
- Blood pressure medication
- Stroke history
- Hypertension
- Diabetes
- Total cholesterol
- Systolic Blood Pressure
- Diastolic Blood Pressure
- BMI
- Heart rate
- Glucose level

Target Variable:

- "TenYearCHD"
  - 0 = No Heart Disease
  - 1 = Heart Disease

Project Workflow

1. Load the dataset.
2. Handle missing values.
3. Perform exploratory data analysis.
4. Select important features.
5. Split the dataset into training and testing sets.
6. Train the Machine Learning model.
7. Evaluate model performance.
8. Predict heart disease risk for new patient data.

Machine Learning Algorithms

The project can use one or more of the following algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Installation

1. Clone the repository.
2. Install the required packages:
   pip install -r requirements.txt
3. Run the Jupyter Notebook or Python script.

Future Enhancements

- Hyperparameter tuning
- Deploy the model using Flask or Streamlit
- Improve prediction accuracy
- Add a user-friendly web interface

Conclusion

This project demonstrates how Machine Learning techniques can be applied to healthcare data for early prediction of heart disease risk. Such predictive models can support healthcare professionals in identifying high-risk individuals and promoting preventive care.
