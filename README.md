# nlp_tweets_classification
Natural Language Processing – Identifying Offensive Posts in Social Media

Offensive content has become pervasive in social media recently, negatively affecting individuals, organisations and the whole society. One of the most common strategies to tackle this problem is to build systems capable of recognising offensive content, which can then be deleted or set aside for human moderation.

In this task, you are given a dataset of tweets that are labelled considering three offensive language categories:
- a. Not Offensive (NOT): Posts that do not contain offense or profanity.
- b. Targeted Insult (TIN): Posts containing insult/threat to an individual, a group, or others.
- c. Untargeted (UNT): Posts containing nontargeted profanity and swearing. Posts with general profanity are not targeted, but they contain non-acceptable language.

Using these data, you need to train a machine learning model to predict the offensive language category of a new tweet. You can use any machine learning algorithm to build the models, either from the sessions or your own research based on the topics we discussed.

## Data set
Within the data folder, there are two .csv files which are named “train.csv” and “test.csv”.

train.csv
Training data to use with model training and validation.
Number of entries: 13240
Columns:
- id – Unique Id
- tweet – Tweet text
- label – Offensive language category (NOT, TIN, UNT)

test.csv
Testing data to use with predictions.
Number of entries: 460
Columns:
- id – Unique Id
- tweet – Tweet text