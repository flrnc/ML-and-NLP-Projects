# **Spam Classification and Dataset Comparison**
This project focuses on classifying SMS messages as spam or ham using the SMSSpamCollection dataset and comparing its performance with the Iris dataset.

## **Key Steps**
1. **Data Loading and Preparation:**
    - Loaded the dataset using pandas.
    - Cleaned text by removing punctuation, applying stemming, and filtering stopwords.
2. **Feature Engineering:**
    - Created features such as message length and punctuation percentage.
3. **Visualization:**
    - Analyzed message length and punctuation distributions using histograms and scatter plots.
4. **Machine Learning Models:**
    - Extracted features with TF-IDF Vectorizer.
    - Applied a Random Forest Classifier to classify messages.
    - Evaluated the model using cross-validation and a holdout test set.
5. **Comparison with Iris Dataset:**
    - Trained and tested a Random Forest model on the Iris dataset.
    - Compared metrics (precision, recall, F1 score, and accuracy) between SMSSpamCollection and Iris datasets.
6. **Key Findings**
    - The Iris dataset demonstrated higher accuracy and better overall performance than the SMSSpamCollection dataset.

## **Tools & Libraries:**
  - Pandas
  - NLTK
  - Matplotlib
  - Seaborn
  - scikit-learn
  - scipy
  - NumPy
