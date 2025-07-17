# Credit score prediction

Goal: This project focuses on building a model to classify credit scores into three categories: 0 (poor), 1 (fair), and 2 (good). Using features like financial behavior and credit history, the goal is to predict creditworthiness accurately. 

Description of dataset: The dataset had 100,000 records. I took the latest dataset from Kaggle. Link- https://www.kaggle.com/datasets/iremnurtokuroglu/credit-score-classification-cleaned-dataset/code

Tasks Performed:
1. Preliminary Analysis- Analyzed charts and classified columns into numerical, categorical and skewed columns.
2. Data Preprocessing- Classified columns into 3 categories and performed transformation.
   a. Numerical columns - Performed imputation and standardization
   b. Skewed columns - Imputation, log transformation and standardization
   c. Categorical columns - One hot encoder
4. Modeling- Used 6 models to test the accuracy score and find the best fit.
   a. Logistic Regression- 66.7% accuracy 
   b. Support Vector Machine- 67.8% accuracy 
   c. Random Forest- 81.5% accuracy
   d. K_Nearest_Neighbor- 77.2% accuracy
   e. Decision Tree- 71.2% accuracy
   f. Naïve-Bayes- 51% accuracy

Conclusion: Random Forest model emerged as the best-performing model, achieving an accuracy of 81.5% on the test set.
