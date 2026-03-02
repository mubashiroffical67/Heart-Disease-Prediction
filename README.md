Heart Disease Prediction Project
=================================

Project Title:
Heart Disease Prediction using Machine Learning

--------------------------------------------
1. Objective
--------------------------------------------
The objective of this project is to build a machine learning model that predicts whether a person is at risk of heart disease based on medical attributes. The project focuses on data preprocessing, exploratory data analysis (EDA), model training, and evaluation using standard classification metrics.

--------------------------------------------
2. Dataset Used
--------------------------------------------
Dataset Name: Heart Disease UCI Dataset
Source: Kaggle / UCI Machine Learning Repository

The dataset contains medical attributes such as:
- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting ECG (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- ST depression (oldpeak)
- Slope
- Number of major vessels (ca)
- Thalassemia (thal)
- Target (0 = No Disease, 1 = Disease)

--------------------------------------------
3. Project Workflow
--------------------------------------------

Step 1: Data Loading
- Loaded dataset using pandas.
- Inspected data using head(), info(), describe().

Step 2: Data Cleaning
- Checked for missing values.
- Handled missing values using median imputation (if required).

Step 3: Exploratory Data Analysis (EDA)
- Visualized target distribution using count plot.
- Used correlation heatmap to identify relationships.
- Plotted histograms and boxplots for understanding distributions.
- Identified key features influencing heart disease.

Step 4: Data Preprocessing
- Split data into training (80%) and testing (20%).
- Applied feature scaling using StandardScaler.

Step 5: Model Training
- Logistic Regression
- Decision Tree Classifier

Step 6: Model Evaluation
- Accuracy Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

--------------------------------------------
4. Model Performance
--------------------------------------------
Logistic Regression:
- Accuracy: ~85% to 88%
- ROC-AUC Score: ~0.88 to 0.92

Decision Tree:
- Comparable accuracy depending on depth parameter.

--------------------------------------------
5. Key Findings
--------------------------------------------
- Chest pain type is one of the strongest predictors.
- ST depression (oldpeak) significantly impacts prediction.
- Maximum heart rate and number of vessels are important features.
- Logistic Regression provided stable and interpretable results.

--------------------------------------------
6. How to Run the Project
--------------------------------------------

1. Install required libraries:
   pip install -r requirements.txt

2. Ensure the following files are in the same folder:
   - Heart_Disease_Prediction.ipynb
   - heart.csv

3. Run Jupyter Notebook:
   jupyter notebook

4. Open the notebook and run all cells sequentially.

--------------------------------------------
7. Technologies Used
--------------------------------------------
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

--------------------------------------------
8. Conclusion
--------------------------------------------
This project demonstrates how machine learning can be applied to medical datasets to predict heart disease risk. The models achieved strong performance and identified key health indicators that influence heart disease prediction.
