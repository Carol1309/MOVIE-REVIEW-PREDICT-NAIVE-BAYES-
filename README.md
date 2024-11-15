# MOVIE-REVIEW-PREDICT-NAIVE-BAYES-
**Objective:**
Develop a text classification model using the Naive Bayes algorithm to analyze the sentiment (positive/negative) of user reviews from multiple datasets.

**Process:**
**Data Preprocessing:**
Loaded text reviews from multiple datasets (amazon data.txt, imdb data.txt, yelp data.txt).
Applied preprocessing (converted text to lowercase and stripped unnecessary characters).

**Feature Extraction:**
Converted text data into numerical format using CountVectorizer, which tokenizes and represents the data in a Bag-of-Words model while removing common stop words.

**Model Training:**
Split the data into training and testing sets using train_test_split.
Trained a Multinomial Naive Bayes model on the vectorized text data.

**Evaluation and Results:**
Evaluated the model using accuracy and a confusion matrix.
Demonstrated the ability to predict sentiment for a sample comment.

**Outcome:**
Successfully built a model to classify the sentiment of user reviews with acceptable accuracy, showcasing the effectiveness of Naive Bayes for text classification tasks.

**Tools and Libraries Used**
**Python Libraries:**
Scikit-learn: For vectorization, model training, and evaluation.
CountVectorizer: To convert text to numeric features.
MultinomialNB: A probabilistic classifier suitable for text data.
Datasets: User reviews from Amazon, IMDb, and Yelp.
