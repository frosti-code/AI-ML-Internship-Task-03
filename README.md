Task 03 – Heart Disease Prediction
Objective
Predict whether a patient has heart disease based on various medical attributes using machine learning models.

Dataset
Source: UCI Heart Disease Dataset

Rows: 303

Columns: 14 (13 features + 1 target variable)

Target Variable: target

0 → No heart disease

1 → Heart disease present

Steps Performed
Data Loading & Preprocessing

Loaded dataset into a Pandas DataFrame.

Checked for missing values and handled them if present.

Encoded categorical variables (if needed).

Split data into training and testing sets.

Exploratory Data Analysis (EDA)

Visualized correlations using a heatmap.

Plotted distributions of key features.

Identified most influential features for prediction.

Model Training

Trained Logistic Regression and Decision Tree Classifier models.

Model Evaluation

Calculated accuracy scores.

Generated confusion matrices and classification reports.

Plotted ROC curve and calculated AUC score.

Displayed feature importance for the Decision Tree model.

Results
Model	Accuracy	Key Notes
Logistic Regression	~85%	Good interpretability, robust results
Decision Tree	~83%	Highlights key features effectively

Most Important Features:

Chest pain type (cp)

Maximum heart rate achieved (thalach)

ST depression (oldpeak)

Number of major vessels (ca)

Thalassemia type (thal)

Insights
Logistic Regression slightly outperformed Decision Tree in accuracy and generalization.

AUTHOR = Muhammad Mustaqeem Javed

ROC curve shows strong model performance for both algorithms.

Medical features such as chest pain type, heart rate, and ST depression have strong predictive power.
