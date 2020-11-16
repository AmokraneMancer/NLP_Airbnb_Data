# NLP on Airbnb Data

Airbnb has successfully disrupted the traditional hospitality industry as more and more travelers decide to use Airbnb as their primary accommodation provider. Since its inception in 2008, Airbnb has seen an enormous growth, with the number of rentals listed on its website growing exponentially each year.

In France, no city is more popular than Paris. That implies that Paris is one of the hottest markets for Airbnb in Europe, with over 66,334 listings as of October 2020.

The following question will drive this project: What do visitors like and dislike?

To find out, we process the reviews to find out what peoples' likes and dislikes are. Natural Language Processing (NLP) and specifically Sentiment Analysis are what we will use here.

## The datasets

I will use the reviews data and combine it with some features from the detailed Paris listings data, sourced from the Inside Airbnb website. Both datasets were scraped on October 12th 2020.
https://drive.google.com/file/d/1apYLfOOkKgZ2QsOeXtvvANr8VUFv_4k8/view?usp=sharing <br />
https://drive.google.com/file/d/1mXwiieSZT2UvwzFetfIorJa8hYw0ULyY/view?usp=sharing

## Table of Contents
1. Obtaining and Viewing the Data <br />
2. Preprocessing the Data <br />

    2.1. Dealing with Missing Values <br />
    2.2. Language Detection <br />

3. Visualizing the Data with WordClouds <br />
4. Sentiment Analysis <br />

    4.1. Get used to VADER package <br />
    4.2. Calculating Sentiment Scores <br />
    4.3. Comparing Negative and Positive Comments <br />
    4.4. Investigating Positive Comments <br />
    4.5. Investigating Negative Comments <br />
