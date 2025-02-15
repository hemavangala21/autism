# autism
This notebook explores the prediction of Autism Spectrum Disorder (ASD) using various machine learning models. It follows a structured pipeline, including data preprocessing, exploratory data analysis (EDA), class imbalance handling with SMOTE, and model training using Decision Tree, Random Forest, and XGBoost. The best-performing model is selected through hyperparameter tuning, and its performance is evaluated using accuracy, confusion matrix, and classification report.

Pipeline Overview:

1. Data Preprocessing:
Handling missing values in categorical features.
Encoding categorical variables using Label Encoding.
Removing irrelevant columns to improve model efficiency.

2. Exploratory Data Analysis (EDA):
Understanding feature distributions using histograms and box plots.
Identifying class imbalance in the target variable.
Checking for correlations between features.

3. Class Imbalance Handling:
Applying Synthetic Minority Oversampling Technique (SMOTE) to balance the dataset.

4. Model Training & Selection:
Training Decision Tree, Random Forest, and XGBoost models.
Performing 5-fold cross-validation to evaluate model performance.
Hyperparameter tuning using RandomizedSearchCV to find the best model.

5. Model Evaluation:
Testing the best-selected model on unseen data.
Evaluating performance using accuracy score, confusion matrix, and classification report.
Saving the best model for future predictions.

Outcome:
The notebook aims to identify the most accurate model for ASD prediction, ensuring high precision and recall to minimize false diagnoses.
