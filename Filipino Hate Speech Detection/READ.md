# **Sentiment Analysis Using LSTM**
This project implements sentiment analysis on text data using Long Short-Term Memory (LSTM) networks, a type of Recurrent Neural Network (RNN). It classifies user comments into "hate" or "non-hate" sentiments based on their content. The dataset consists of Filipino language comments, and preprocessing steps such as text cleaning, tokenization, and stopword removal were applied before training the LSTM model.

## **Key Highlights**
  - Preprocessing of text data, including removing HTML tags, punctuation, and stopwords.
  - Tokenization and padding of text data for input into an LSTM model.
  - Binary classification of comments into hate and non-hate categories.
  - Evaluation of model performance using accuracy score and classification report.
  - Application of the trained model on new comment data to predict sentiments.
  - Use of LSTM to capture long-range dependencies and contextual information in text.
  - Implementation of early stopping to prevent overfitting and improve model generalization.
  - Creation of confusion matrix to assess the performance of the classification model.
  - Hyperparameter tuning to optimize LSTM model's performance.
  - Visualization of training and validation accuracy/loss over epochs for model evaluation.
  - Deployment-ready model for real-time sentiment prediction on Filipino text data.

## **Tools and Libraries**
  - Keras
  - TensorFlow
  - NLTK (Natural Language Toolkit)
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Advertools (for stopword removal)
