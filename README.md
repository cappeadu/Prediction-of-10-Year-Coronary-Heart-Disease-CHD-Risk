# Prediction-of-10-Year-Coronary-Heart-Disease-(CHD)-Risk
This project utilizes machine learning algorithms to predict the 10-year risk of Coronary Heart Disease (CHD)
The dataset includes various features such as age, BMI, blood pressure (both diastolic and systolic), heart rate, cholesterol levels, glucose levels, and daily cigarette consumption.

# Key Steps in the Process:
### Data Preprocessing:

**Imputation**: Missing values for features such as cigarettes per day, total cholesterol, and BMI are handled using mean imputation.

**Encoding and Standardization**: Categorical variables are one-hot encoded, and numerical features are standardized.

**Normalization**: Log transformation is applied to normalize data distributions.

### Data Splitting and Balancing:

**Split**: The dataset is divided into a training set (75%) and a test set (25%).

**Balancing**: Due to an imbalanced diagnosis class, both Random Undersampling and Synthetic Minority Oversampling Technique (SMOTE) are applied to achieve class balance.
Machine Learning Models:

The following models are evaluated: 
- Logistic Regression
- Random Forest with SMOTE
- Support Vector Classifier (SVC) with SMOTE
- XGBoost with SMOTE

Model performance is assessed through metrics such as Accuracy, ROC-AUC Score, Receiver Operating Characteristic (ROC) Curve, and Recall.

## Exploratory Data Analysis (EDA):

Distribution analysis is conducted for each feature, including a breakdown of counts by diagnosis class, age, gender, and lifestyle factors like smoking.

## Feature Importance:
SHAP (SHapley Additive exPlanations) analysis is used to identify feature importance, highlighting which factors most contribute to the CHD risk prediction.

## Results
The project evaluates each model based on key metrics: Accuracy, ROC-AUC Score, and Recall values for each model help determine the most effective algorithm for CHD risk prediction.
