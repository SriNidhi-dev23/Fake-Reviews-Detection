# Fake Reviews Detection

## Problem Statement

The aim of this project is to identify deceptive or computer-generated product reviews from a diverse dataset containing categories such as Sports, Home & Office, and more. Each review is associated with a rating and a label: OR (Original Review by a human) or CG (Computer Generated review). The primary objective is to classify whether a review is authentic or artificially generated.

## Project Overview

This project utilizes a balanced dataset comprising 40,000 product reviews—20,000 legitimate reviews written by real users and 20,000 artificially generated fake reviews. The model is trained to differentiate between genuine and fabricated reviews based solely on textual content.

## Python Libraries and Dependencies

The implementation involves several essential Python libraries:

<ul>
  <li>numpy</li>
  <li>pandas</li>
  <li>matplotlib.pyplot</li>
  <li>seaborn</li>
  <li>warnings</li>
  <li>nltk</li>
  <li>nltk.corpus</li>
  <li>string</li>
  <li>scikit-learn modules:
    <ul>
      <li>naive_bayes</li>
      <li>feature_extraction</li>
      <li>model_selection</li>
      <li>ensemble</li>
      <li>tree</li>
      <li>linear_model</li>
      <li>svm</li>
      <li>neighbors</li>
    </ul>
  </li>
</ul>

## Text Preprocessing Techniques

The dataset underwent several preprocessing steps to make it suitable for model training:

<ul>
  <li>Removal of punctuation marks</li>
  <li>Conversion of text to lowercase</li>
  <li>Filtering out stopwords</li>
  <li>Application of stemming</li>
  <li>Lemmatization for word normalization</li>
  <li>Elimination of numeric characters</li>
</ul>

## Text Vectorization and Feature Extraction

The textual data was converted into numerical format using the following methods:

<ul>
  <li>CountVectorizer (Bag of Words model)</li>
  <li>TF-IDF (Term Frequency–Inverse Document Frequency)</li>
</ul>

## Machine Learning Models Used

Several supervised learning algorithms were applied to classify the reviews:

<ol>
  <li>Logistic Regression</li>
  <li>K-Nearest Neighbors (KNN)</li>
  <li>Support Vector Machine (SVM)</li>
  <li>Decision Tree Classifier</li>
  <li>Random Forest Classifier</li>
  <li>Multinomial Naive Bayes</li>
</ol>

## Model Performance Summary

<ul>
  <li>The Support Vector Machine model delivered the highest classification accuracy, achieving around 88%.</li>
  <li>Logistic Regression followed closely with an accuracy of approximately 86%.</li>
  <li>Random Forest and Naive Bayes models both attained roughly 84% accuracy.</li>
  <li>Decision Tree Classifier achieved a moderate accuracy of about 73%.</li>
  <li>K-Nearest Neighbors showed the least effectiveness, with accuracy close to 58%.</li>
</ul>

## License

This project is distributed under the Creative Commons Attribution 4.0 International License (CC-BY 4.0).
