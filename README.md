# Sentiment-Analysis-Amazon-Fine-Food-Reviews

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

Attribute Information:

- Id
- ProductId: unique identifier for the product
- UserId: unqiue identifier for the user
- ProfileName
- HelpfulnessNumerator: number of users who found the review helpful
- HelpfulnessDenominator: number of users who indicated whether they found the review helpful or not
- Score: rating between 1 and 5
- Time: timestamp for the review
- Summary: brief summary of the review
- Text: text of the review

## Objective

Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).


## Dataset Used

Out of the total dataset, for this study a balanced subset of the dataset was chosen randomy consisting of 5000 positively labelled reviews and 5000 negatively labelled reviews.

## Text cleaning tasks done:

- Removing words with HTML tags
- Removing URLs
- Converting all words to lowercase
- Removing all special characters and punctuation marks
- Removing alpha-numeric words
- Removing Stopwords
- Stemming

## Techniques used for preprocessing of data:

- Bag of Words
- TF-IDF vectorizer
- Word2Vec: Avg w2v and TF-IDF weighted w2v

## Performance metrics

- Accuracy
- Confusion Matrix
- Classification report
- AUC
- ROC curve
