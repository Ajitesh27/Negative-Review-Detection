# Negative-Review-Detection

Sentiment analysis is part of the Natural
Language Processing (NLP) techniques
that consists in extracting emotions
related to some raw texts. This is usually
used on social media posts and customer
reviews in order to automatically
understand if some users are positive or
negative and why. The goal of this study is
to show how sentiment analysis can be
performed using python and detect the
negative reviews given by the user.

We used some 515k hotel reviews
data present on kaggle. Each
observation consists in one
customer review for one hotel.
Each customer review is composed
of a textual feedback of the
customer’s experience at the hotel
and an overall rating. 

For each textual review, we want to predict if it corresponds to a good review
(the customer is happy) or to a bad one (the customer is not satisfied). The
reviews overall ratings can range from 2.5/10 to 10/10. In order to simplify the
problem we will split those into two categories:<br>
● bad reviews have overall ratings < 5<br>
● good reviews have overall ratings >= 5<br>
The challenge here is to be able to predict this information using only the raw
textual data from the review.
