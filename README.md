Heart Disease Prediction
🧠 Project Overview
This project focuses on predicting the likelihood of heart disease in individuals using machine learning techniques. The dataset contains medical attributes of patients such as age, cholesterol levels, blood pressure, etc. Based on this, a classification model is trained to predict the presence or absence of heart disease.

🔍 Objective
To build an accurate and reliable heart disease prediction model.

To compare Logistic Regression and Random Forest Classifier.

To improve accuracy using hyperparameter tuning and cross-validation.

🛠️ Tools & Technologies
Python

Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

📊 Models Used & Performance
1. Logistic Regression
Accuracy on Test Data: 97.36%

Accuracy on Train Data: 99.34%

Cross-Validation Accuracy: 98.23% ± 1.32

F1 Score: 0.96

Precision: 0.9756

Recall: 0.9523

2. Random Forest Classifier
Accuracy on Test Data: 94.73%

Cross-Validation Accuracy: 96.49% ± 4.53

F1 Score: 0.93

Precision: 0.9761

Recall: 0.8913

3. Final Logistic Regression (after Hyperparameter Tuning)
Accuracy: 98.45%

Best Parameters: solver='saga', penalty='l2', C=0.5
