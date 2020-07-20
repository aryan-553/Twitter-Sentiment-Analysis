
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

Full tweet texts are provided with their labels for training data.
Mentioned users' username is replaced with @user.

the classification model used is linear regression
the precision was approx 80% but it is not visible in github since the colab was crashing due to max usage of RAM at specifying test data
got 80% precision and 95% accuracy on local machine
