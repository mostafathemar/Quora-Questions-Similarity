# Quora-Questions-Similarity
(case studies) Advanced machine learning techniques and natural language processing to identify duplicate questions in the Quora dataset.

# Introduction
This project aims to identify duplicate questions in the Quora dataset, leveraging advanced machine learning techniques and natural language processing. Our model can detect semantically similar questions, providing significant value for content moderation and improving search efficiency.

# Technologies

1. Python
2. Pandas
3. Numpy
4. Scikit-learn
5. NLTK
6. SQLite
7. XGBoost

# Dataset
The Quora dataset is used in this project, which contains pairs of questions. Our task is to predict whether the questions in the pair are semantically equivalent from Kaggle.

# Methodology

1. Exploratory Data Analysis and Data Loading
We begin by loading the data and conducting exploratory data analysis to better understand our dataset. We examine the structure, handle missing values, and conduct some preliminary analyses to understand the data we're working with.

2. Preprocessing
We perform various preprocessing steps on the text data, which include handling missing values, removing stop words, tokenizing, stemming, and lemmatization.

3. Featuring Text Data with TFIDF Weighted Word-Vectors
Here, we transform our cleaned and tokenized text data into a numerical format via TFIDF-weighted word vectors. We create a TFIDF vectorizer, fit it to our text data, and transform our text data into these weighted word vectors.

4. Machine Learning Models
We train various machine learning models on the engineered features to predict whether two questions are duplicates. The models used in this project include:

  1. Random model
  2. Logistic regression with SGD classifier
  3. Linear SVM with SGD classifier
  4. XGBoost
    
  We evaluate the performance of these models using metrics like log-loss, confusion matrix, precision matrix, and recall matrix.

# Running the Scripts

1. Run the data loading and exploratory data analysis script.
2. Run the preprocessing script to clean and prepare the data.
3. Run the feature engineering script to convert text data into TFIDF-weighted word vectors.
4. Run the model training scripts to train the models and evaluate their performance.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Contact
For any queries, please feel free to reach out to us at mostafathemar@email.com.
