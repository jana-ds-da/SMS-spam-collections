# SMS-spam-collections# 

📩 Spam Message Classification using Machine Learning

This project is a simple machine learning model that classifies SMS messages as **Spam** or **Not Spam** using text data.

## 🧠 Objective

Build a basic classification model that can automatically detect spam messages using supervised learning techniques.

## 📊 Dataset

The dataset contains labeled SMS messages:

* Spam
* Ham (Not Spam)

## ⚙️ Steps

* Loaded and explored the dataset
* Preprocessed and cleaned the text data
* Converted text into numerical features using **TF-IDF Vectorization**
* Split the data into training and testing sets
* Trained a **Naive Bayes (MultinomialNB)** model
* Trained a **Logistic Regression** model for comparison
* Evaluated models using accuracy, precision, recall, and F1-score
* Applied threshold tuning to improve recall for spam detection

## ⚠️ Challenge

The initial models had good accuracy but lower recall for spam messages, meaning some spam messages were missed.

## 🛠️ Solution

* Focused on recall as an important evaluation metric
* Adjusted classification threshold (0.5 → 0.3)
* Improved spam detection performance significantly

## 📈 Results

* Achieved high accuracy (~98%)
* Improved recall for spam detection after tuning
* Logistic Regression performed better after optimization
