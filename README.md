# Amazon-Reviews-Sentiment-Analysis

    The Amazon Fine Food Reviews dataset consists of 568,454 food reviews Amazon users left up to October 2012.

# Dataset statistics
    Number of reviews     568,454
    Number of users     256,059
    Number of products     74,258
    Users with > 50 reviews     260
    Median no. of words per review 56
    Timespan     Oct 1999 - Oct 2012

# Dataset Fields Description:
    This dataset consists of a single CSV file, Reviews.csv, and a corresponding SQLite table named Reviews in database.sqlite. 
    The   columns in the table are:
    Id - Unique row number
    ProductId - unique identifier for the product
    UserId - unqiue identifier for the user
    ProfileName
    HelpfulnessNumerator - number of users who found the review helpful
    HelpfulnessDenominator - number of users who indicated whether they found the review helpful
    Score - rating between 1 and 5
    Time - timestamp for the review
    Summary - brief summary of the review
    Text - text of the review

The data is provided on this link :https://www.kaggle.com/snap/amazon-fine-food-reviews/data

# Objective:

     Analysing the data & plot the required graphs to show that these conclusions are true:
     a. Positive reviews are very common.
     b. Positive reviews are shorter.
     c. Longer reviews are more helpful.
     d. Despite being more common and shorter, positive reviews are found more helpful.
     e. Frequent reviewers are more discerning in their ratings, write longer reviews, and write more helpful reviews
