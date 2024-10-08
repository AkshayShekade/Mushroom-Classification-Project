# Mushroom Classification Using Machine Learning

### Overview:

This project aims to classify mushrooms as edible or poisonous based on their physical characteristics using various machine learning algorithms. The dataset used is sourced from the UCI Machine Learning Repository and contains features such as cap shape, color, stem size, and habitat.

### Table of Contents:

- Overview
- Project Structure
- Dataset
- Data Preprocessing
- Modeling
- Evaluation
- Conclusion

### Dataset:

The dataset contains 61069 samples with 21 categorical features describing various physical characteristics of mushrooms. The target variable is binary:

- e = edible
- p = poisonous
  
### Some of the key features include:

- Cap Shape
- Cap Color
- Stem Height
- Gill Color
- Habitat
  
### Data Preprocessing:

- Feature Encoding: Categorical features were encoded using Label Encoding.
- Standardization: Numerical features were standardized using StandardScaler to improve model performance.
Modeling

### Several machine learning algorithms were used to build the classification model:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Classifier (SVC)

### Model Selection and Hyperparameter Tuning:

- RandomForestClassifier was further optimized using GridSearchCV to find the best hyperparameters.
- Cross-validation was used to validate model performance.

### Evaluation:

The models were evaluated using the following metrics:

- Accuracy
- ROC-AUC Score
- Confusion Matrix

#### The Random Forest model achieved the best performance with:

- Accuracy: 99%
- ROC-AUC: 1.00
  
### Conclusion:

- RandomForestClassifier emerged as the best-performing model, showing excellent discriminatory power between edible and poisonous mushrooms.
- The model can help in automating the classification of mushrooms based on physical attributes, aiding mushroom foragers in making safer decisions.
