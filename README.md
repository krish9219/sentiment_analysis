# Sentiment Analysis


### Data Set

Data set consists of 50,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of 0, and rating >=7 have a sentiment score of 1. No individual movie has more than 30 reviews. Data set is divided into train 25,000 & test 25,000 and in a format of (.tsv).

### Data fields

id - Unique ID of each review </br>
sentiment - Sentiment of the review; 1 for positive reviews and 0 for negative reviews </br>
review - Text of the review

![center](./images/data.png)

### Libraries used

Pandas, Numpy, sklearn, NLTK, BeautifulSoup


#### Cleaning

![center](./images/cleaning.png)

### Model

![center](./images/result.png)

### Result

A basic Random Forest model has predicted the sentiment with an accuracy of **84%** and my Out of Bag score is **83%**. Tuning model further with RandomsearchCV improves model performance further.
