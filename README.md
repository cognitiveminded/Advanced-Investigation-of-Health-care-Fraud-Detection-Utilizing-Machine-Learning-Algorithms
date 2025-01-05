Machine Learning Code for Fraud Detection
This repository contains a comprehensive machine learning workflow for fraud detection using healthcare data. The code includes steps for data loading, preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation. The goal is to predict potential fraud in healthcare claims.

Key Features
Data Loading: Loads multiple datasets including train, test, beneficiary, inpatient, and outpatient data.

Data Preprocessing: Handles missing values, replaces categorical values, and calculates age from date of birth.

Feature Engineering: Creates new features such as 'WhetherDead' and 'TotalClaims'.

Model Training: Implements multiple machine learning models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.

Hyperparameter Tuning: Uses GridSearchCV to find the best parameters for the Gradient Boosting model.

Evaluation: Evaluates models using accuracy, ROC AUC score, and classification report.

Final Prediction: Makes predictions on the test set and saves the results to a CSV file.

How to Use
Clone the Repository:

git clone https://github.com/yourusername/machine-learning-code.git
cd machine-learning-code
Install Dependencies:

pip install -r requirements.txt
Run the Code:

python machine_learning_code.py
View Results: The final predictions will be saved in submission.csv.

Requirements
Python 3.x

Libraries: numpy, pandas, scipy, seaborn, matplotlib, scikit-learn, imbalanced-learn

Contributing
Feel free to fork the repository, make changes, and submit pull requests. Any contributions are welcome!

License
This project is licensed under the MIT License.
