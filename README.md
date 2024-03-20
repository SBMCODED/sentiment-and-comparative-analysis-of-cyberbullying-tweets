The code creates a mapping label_map where sentiment labels ('positive', 'negative', 'neutral') are assigned numeric values (0, 1, 2).
The map() function is used to convert the sentiment labels in the dataset y to their corresponding numeric values.
Evaluating the Models
A function evaluate_model(y_true, y_pred) is defined to calculate accuracy, precision, recall, and F1-score.
The function uses accuracy_score(), precision_score(), recall_score(), and f1_score() from scikit-learn.
The Logistic Regression, Naive Bayes, and LSTM models are evaluated using the evaluate_model() function.
This code is part of a sentiment analysis and comparative analysis project for cyberbullying tweets. It includes:

Mapping sentiment labels to numeric values.
Training and evaluating Logistic Regression, Naive Bayes, and LSTM models for sentiment analysis.
The goal is to analyze sentiment and compare the performance of these models for different types of cyberbullying.
