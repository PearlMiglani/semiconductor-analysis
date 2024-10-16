This project implements classification of industry using scikit-learn pipeline that includes data preprocessing steps. The following classifiers are implemented for comparison:
KNN
Decision Tree Classifier
Support Vector Machine (SVM)
Naive Bayes Classifier

Evaluation Metrics
The model performance is evaluated using:
Confusion Matrix: Displays the counts of true positive, true negative, false positive, and false negative predictions.
Classification Report: Provides precision, recall, F1-score, and support for each class.
Accuracy Score: The overall accuracy of the model.

Data Description
Rank: The rank of the company based on market capitalization.
Market Cap (USD): The market capitalization of the company in USD.
Country: The country where the company is based.
Industry: The industry of the company.
Sector: The target variable, representing the sector of the company.
Model Implementation

Data Source Reference - Semiconductor Companies of The World Database
By Girum B WondemagegnContainer: Kaggle.comYear: 2024URL: https://www.kaggle.com/datasets/girumwondemagegn/semiconductor-companies-of-the-world-by-market-cap/data
