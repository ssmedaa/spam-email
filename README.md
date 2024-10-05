# Spam Email Classification

## Description
Created a machine learning algorithm for spam email detection that utilizes natural language processing (NLP) and machine learning techniques to categorize emails as either spam or legitimate.

## Steps
  1. Data Collection & Preprocessing
     - [Kaggle Email dataset](https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset?resource=download)
  2. Data Analysis
     - Analyzing spam emails from legitimate emails, and the top 20 frequent words. 
  4. Model Training & Evaluating 
     - Logistic Regression: Supervise ML algorithm of binary classifications by predicting email and categorizing as either: spam or legitimate.
     - Model metrics evaluation of:
       accuracy= ![Formula](https://latex.codecogs.com/svg.image?\frac{TP&plus;TN}{TP&plus;TN&plus;FP&plus;FN})
       percision= ![Formula](https://latex.codecogs.com/svg.image?\frac{TP}{TP&plus;FP})
       recall= ![Formula](https://latex.codecogs.com/svg.image?\frac{TP}{TP&plus;FN})
       f1-score= ![Formula](https://latex.codecogs.com/svg.image?\frac{2\times&space;precision\times&space;recall}{precision&plus;recall})
  5. Testing
     - Use model to test new message, to check accuracy in models prediction ability

