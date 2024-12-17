# Water-Potability-Prediction
A machine learning project to predict water potability using regression models and advanced data preprocessing techniques.

# Project Overview
This project aims to predict the potability of water based on multiple water quality parameters such as pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, and others. It addresses a regression problem and uses median absolute error as the key evaluation metric.

# Key Features:
* Data Cleaning & Preprocessing:
1. Handling missing values.
2. Outlier detection and removal using IQR.
3. Log transformations for skewed features.
4. Feature scaling and normalization.
* Exploratory Data Analysis (EDA):
1. Correlation analysis to identify relationships between features and the target variable.
2. Visualization of key trends and distributions.
* Model Implementation:
1. Implementation of various regression models:
Linear Regression, Ridge, Lasso, Random Forest, Decision Tree,  Support Vector Regression (SVR), K-Nearest Neighbors (KNN)
2. Hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
* Model Evaluation:
Use of k-fold cross-validation to validate model performance.
* Evaluation metric:
Score=max(0,100×(1−Median Absolute Error))
# Technologies Used
* Python (Pandas, NumPy, Scikit-learn)
* Data Visualization: Matplotlib, Seaborn
* Jupyter Notebook
# How to Run the Project
1. Clone the repository:
git clone https://github.com/your-username/Water-Potability-Prediction.git
cd Water-Potability-Prediction
2. Install required libraries:
pip install -r requirements.txt
3. Run the notebook:
Open water_potability.ipynb in Jupyter Notebook or any Python IDE.

# Future Scope
* Incorporate advanced models like XGBoost and CatBoost for improved performance.
* Deploy the model as an API using Flask or FastAPI.
* Add interactive visualizations using Dash or Streamlit.
# Contributions
Feel free to contribute! Fork the repository, make your changes, and submit a pull request.
