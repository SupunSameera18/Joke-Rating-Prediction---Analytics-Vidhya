# Joke-Rating-Prediction---Analytics-Vidhya
This practice problem challenges the participants to predict the ratings for jokes given by the users provided the ratings provided by the same users for another set of jokes. This dataset is taken from the famous jester online Joke Recommender system dataset.

The dataset contains anonymous ratings(-10 to 10) provided by a total of 41,000 users. Train file contains 1.1 million ratings and in the test file the user needs to predict the ratings provided by the same set of users on a diffrent set of jokes. The complete text for all 139 jokes is also provided in a separate csv. Given the combination of user and joke, the task is to predict the rating given by that user to the joke in the test set

Public Private Split
Private split contains 60% of jokes from the test file rated by each user, while the public split contains the other 40% rated by the same user.

Evaluation Metric
The evaluation metric for this challenge is root mean squared error (RMSE)
