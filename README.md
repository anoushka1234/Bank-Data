# Bank-Data
Machine Learning classification project aimed at predicting whether a bank client will subscribe to a term deposit based on various demographic, financial, and marketing-related features.

The steps I took to build this project were the following:

1.Data Cleaning  and Preprocessing-- removing null values, encoding string values to numerical,dropping irrelevant columns, grouping categories in categorical columns (reducing number of categories via merging),Applied StandardScaler() to numerical features for better compatibility with certain models.

2.Train Test Split -- Split the dataset into training and testing sets using train_test_split() to ensure the models are evaluated on unseen data.

3. Model Building -- Implemented multiple models including:Logistic Regression,Decision Tree,Random Forest,Support Vector Machine (SVM),k-Nearest Neighbors (kNN)
   
4.Model Evaluation -- Evaluated each model using the following metrics: Accuracy Score,Precision Score,Recall Score,F1 Score,Confusion Matrix,Classification Report

5.Comparative Analysis -- Compared all models based on their performance metrics to identify the most effective model.Identified the Random Forest model as having signs of overfitting.

6.Applied Hyperparameter Tuning to improve the performance of models (especially Random Forest).Used Cross-Validation to reduce the risk of overfitting and ensure more reliable model performance.
