# Building Energy Use Project

## Description

This project focuses on selecting, transforming, and creating relevant features for both supervised and unsupervised learning models to achieve optimal performance in predicting building energy use.

## Techniques Utilized

- **Identification of Categorical Variables** :
  - Identification and transformation of qualitative variables using OneHotEncoder or TargetEncoder.

- **Creation of New Features** :
  - Feature engineering from existing data.

- **Mathematical Transformations** :
  - Adjusting variable distributions as needed.

- **Normalization of Variables** :
  - StandardScaler
  - MinMaxScaler

- **Supervised Learning Models** :
  - Target variable selection for total energy consumption and CO2 consumption.
  - Ensuring no data leakage by checking for variables too correlated with the target.

- **Model Evaluation Metrics** :
  - R2
  - RMSE
  - MAE

- **Performance Indicators** :
  - Exploring additional performance indicators beyond scores, such as variable coefficients under penalization, error visualization, and computation time.

- **Train/Test Data Split** :
  - Properly splitting data to evaluate model performance and detect overfitting.

- **Cross-Validation** :
  - Implementing cross-validation using GridSearchCV for hyperparameter optimization.

- **Algorithm Testing** :
  - Testing  4 different algorithm families  ElasticNet, SVM, XGBOOST, RandomForest) and comparing summary of the results.
  - Justifying the final choice of algorithm and hyperparameters.

- **Feature Importance Analysis** :
  - Conducting both global and local feature importance analysis on the entire dataset and on individual instances using SHAP method.


