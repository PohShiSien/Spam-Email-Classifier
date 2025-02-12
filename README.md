# 📧 Spam Email Classifier using Machine Learning
🚀 A machine learning project to classify emails as Spam or Ham (Not Spam) using Natural Language Processing (NLP) and Logistic Regression.

🔍 Overview
This project builds a spam detection system using machine learning techniques. It processes raw email text, extracts features, and applies a Logistic Regression model to classify emails. The dataset used is the Apache SpamAssassin Public Corpus.

📌 Features
✔ Preprocesses raw emails (removes headers, converts to lowercase, replaces URLs, numbers, and punctuation).
✔ Extracts text features (word counts, stemming, and vectorization).
✔ Uses a Logistic Regression model for classification.
✔ Implements cross-validation to evaluate model performance.
✔ Supports API deployment for real-time email classification.

🛠️ Tech Stack
Programming Language: Python 🐍
Libraries: Scikit-Learn, Pandas, NumPy, SciPy, NLTK
ML Model: Logistic Regression (with lbfgs solver)
Deployment: Flask (optional for API)

📊 Dataset Details
Ham (legitimate emails): datasets/easy_ham/
Spam emails: datasets/spam/
Preprocessing:
Remove headers
Convert to lowercase
Replace URLs, numbers, punctuation
Apply stemming & tokenization
