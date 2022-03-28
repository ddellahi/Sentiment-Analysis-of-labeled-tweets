# Sentiment-Analysis-of-labeled-tweets

<a name="back"></a>
## Table of contents
1. [Data analysis](#application)
    1. [Learning About Our Data Set With Exploratory Data Analysis](#subparagraph1)
2. [Creating features](#paragraph1)
3. [Experimental protocol (learning/validation/testing)](#paragraph2)
    1. [Spliting Training and Testing Data](#subparagraph31)
    1. [Measuring the Performance of a MultinomialNB Machine Learning Model](#subparagraph32)
4. [Testing new data](#paragraph3)
    1. [Testing on some negative tweets](#subparagraph41)
    1. [Testing on some positive tweets](#subparagraph42)
    1. [Testing on some mixt tweets](#subparagraph43)

## About Dataset

### Context
This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .

### Content
It contains the following 6 fields:

1. target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

2. ids: The id of the tweet ( 2087)

3. date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)

4. flag: The query (lyx). If there is no query, then this value is NO_QUERY.

5. user: the user that tweeted (robotickilldozr)

6. text: the text of the tweet (Lyx is cool)
