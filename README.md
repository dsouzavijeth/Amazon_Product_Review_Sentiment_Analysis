# Amazon_Product_Reviews

The datset contains following features:
1. name - Name of the product
2. brand - The product brand
3. categories - The category of the product
4. primaryCategories - The primary category to which the product belongs
5. reviews.date - The date on which the reviews were given for the product
6. reviews.text - Reviews for the product
7. reviews.title - The title of the review
8. sentiment - Sentiment (Positive / Negative)

For analysing the sentiments for the product reviews, the columns considered are:
1. reviews.text 
2. reviews.title
3. sentiment

Folowing steps are considered for text processing:
1. Removing punctuations
2. Removing stopwords
3. Tokenizing words
4. Lemmatization
5. Creating the Bag of Words
6. Tfidf Transformation

Model selection is performed using:
1. Multinomial Naive Bayes Classifier
2. Random Forest Classifier
3. XGBoost
4. Support Vector Machine (SVM) Classifier
5. LSTM (Long Short Term Memory)
