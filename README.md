SCENARIO 1 – Bagging (Diabetes Prediction)

This project focuses on predicting whether a patient has diabetes using the Diabetes Dataset. The target variable is Outcome, where 0 represents no diabetes and 1 represents diabetes. Important input features include Glucose level, BMI, Age, Blood Pressure, and other medical attributes. First, the dataset is loaded and a Decision Tree model is trained as a baseline model. After that, the BaggingClassifier is applied to improve the performance by reducing variance and increasing stability. Finally, the accuracy of the Decision Tree and Bagging models are compared. Visualization includes an accuracy comparison bar graph and a confusion matrix to clearly understand the model performance.

SCENARIO 2 – Boosting (AdaBoost & Gradient Boosting – Customer Churn Prediction)

This project aims to predict whether a customer will churn using the Telco Customer Churn Dataset. The target variable is Churn (Yes/No) and the input features include Tenure, Monthly Charges, and Contract Type. In this scenario, boosting techniques are used to improve prediction accuracy. Two models are trained: AdaBoost and Gradient Boosting. Both models are evaluated and their performances are compared to identify which boosting technique works better for the churn dataset. Visualization includes the ROC Curve to analyze model performance and a Feature Importance plot to identify the most influential features affecting customer churn.

SCENARIO 3 – Random Forest (Income Prediction)

This project focuses on predicting whether a person earns more than 50K salary using the Adult Income Dataset. The target variable is Income (>50K or <=50K) and the input features include Age, Education, Occupation, and Hours-per-week. A Random Forest model is trained because it combines multiple decision trees and improves accuracy while reducing overfitting. The number of trees in the forest is tuned to observe how the performance changes. The model is then evaluated using accuracy and other performance metrics. Visualization includes Feature Importance to understand which features affect salary prediction and a graph showing Accuracy vs Number of Trees.

SCENARIO 4 – Stacking (Heart Disease Prediction)

This project aims to predict the presence of heart disease using the Heart Disease Dataset. The target variable is Presence of Heart Disease (0/1) and the input features include Cholesterol, Maximum Heart Rate, Age, and other medical attributes. In this scenario, multiple base models are trained including Logistic Regression, Support Vector Machine (SVM), and Decision Tree. These models are then combined using a StackingClassifier to improve prediction accuracy. The performance of the stacked model is compared with the individual models. Visualization includes a model comparison bar chart to clearly show how stacking improves the overall performance.

SCENARIO 5 – SMOTE (Fraud Detection)

This project focuses on detecting fraudulent transactions using the Credit Card Fraud Detection Dataset. The target variable is Fraud (0 = Normal, 1 = Fraud) and the input features include Transaction Amount, Time, and PCA-transformed features. Since the dataset is highly imbalanced, the class distribution is first analyzed. Then, SMOTE (Synthetic Minority Oversampling Technique) is applied to balance the dataset. A model is trained before and after applying SMOTE to compare performance improvements. Visualization includes class distribution graphs (before and after SMOTE) and a Precision-Recall Curve to evaluate the model more effectively on imbalanced data.

# 24ADI003_RAMYA-R_24BAD096_EX6
