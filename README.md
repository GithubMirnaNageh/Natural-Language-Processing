Amazon Alexa Sentiment Analysis

📌 Project Overview

This project performs sentiment analysis on Amazon Alexa product reviews. It utilizes Random Forest, Decision Tree, and XGBoost machine learning models to classify customer feedback as positive or negative. The goal is to analyze user opinions and improve customer insights.

📂 Repository Structure

🔧 Installation & Setup

Clone the repository

Install dependencies

Run the Jupyter Notebook

Open Amazon_alexa.ipynb and execute the cells.

📊 Dataset

The dataset amazon_alexa.csv contains Amazon Alexa customer reviews.

Key features:

verified_reviews: The text of the review.

feedback: 1 (Positive) or 0 (Negative) sentiment label.

🏗️ Model Training & Evaluation

Three machine learning models are implemented:

Random Forest: An ensemble learning method for classification.

Decision Tree: A simple and interpretable model.

XGBoost: A powerful gradient boosting model.

Steps:

Text Preprocessing: Tokenization, removing stopwords, stemming.

Feature Extraction: Using CountVectorizer.

Model Training: Training Random Forest, Decision Tree, and XGBoost.

Evaluation Metrics: Confusion Matrix

🚀 Results

Model

Accuracy

Random Forest

0.9428571428571428

Decision Tree

0.9185185185185185

XGBoost

0.9417989417989417

📌 Future Improvements

Implement Deep Learning models (e.g., LSTMs, BERT).

Optimize hyperparameters for better performance.

Expand dataset with more customer reviews.
