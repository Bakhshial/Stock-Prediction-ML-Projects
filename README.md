# Stroke Prediction Using Machine Learning
### Overview
Stroke is one of the leading causes of death and disability worldwide. Early prediction of stroke can help in timely interventions, potentially saving lives. This project leverages machine learning to predict the likelihood of stroke in individuals based on demographic and health-related features.

### Problem Statement
This project aims to develop a predictive model that accurately identifies individuals at risk of stroke using clinical and lifestyle data.


### Dataset
**Source:**  https://www.kaggle.com/competitions/playground-series-s3e2/data
**Features:**
   *Demographic:* Age, gender, etc.
   *Health metrics:* hypertension,BMI, glucose levels, heart disease, etc.
   *Lifestyle factors:* Smoking status.
   *Target:* Binary classification (1 = Stroke, 0 = No Stroke).
   *Size:* [15304 rows, 12 columns]
### Technologies Used
**Python:** Data preprocessing, model development, and evaluation.
**Libraries:**
    **Data Processing:** pandas, numpy.
    **Visualization:** matplotlib, seaborn.
    **Machine Learning:** scikit-learn, XGBoost.
    **Flask:** For model deployment with a front-end interface.


### Steps Followed

#### 1. Data Preparation
*Dataset:* Health-related attributes such as age, BMI, glucose levels, and smoking status were utilized.

*Preprocessing:* Handled missing values, performed one-hot and ordinal encoding, and scaled numerical features.

*Imbalanced Data Handling:* Applied SMOTE (Synthetic Minority Oversampling Technique) to address the imbalance in stroke cases.

#### 2. Exploratory Data Analysis (EDA)

    Visualized numerical and categorical data distributions.
    Explored correlations between features and the target variable.
    Detected and treated outliers using the IQR method.
    
#### 3. Model Training and Evaluation
Trained multiple machine learning models, including:

      Logistic Regression
      Random Forest
      Gradient Boosting
      Decision Tree
      Support Vector Machine (SVM)
      K-Nearest Neighbors (KNN)
      Naive Bayes
      Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
      Used Voting Classifiers (Hard and Soft) for ensemble predictions.
#### 5. Confusion Matrices and ROC Curves
Plotted confusion matrices for all models to visualize performance.

Combined ROC curves to compare the models' true and false positive rates.
