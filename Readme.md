# Email Spam Detection using Support Vector Machines (SVM)

This repository contains code for Email Spam Detection using Support Vector Machines (SVM). The SVM algorithm is a popular choice for text classification tasks like spam detection due to its effectiveness in separating classes in high-dimensional spaces.


# Dependencies:

Pandas: For efficient data handling and preprocessing.
    
scikit-learn (sklearn): Provides tools for machine learning tasks such as feature extraction (CountVectorizer), data splitting (train_test_split), and SVM implementation (svm).


# Dataset

The dataset used in this project contains labeled examples of emails, with each email labeled as either spam or non-spam (ham). It is available in the emails.csv file. Each row in the CSV file represents an email, with the first column containing the email text and the second column containing the corresponding label (0 for ham, 1 for spam).