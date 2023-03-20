# Modeling-and-Learning-from-Data

The following methods were implemented and evaluated in order to find the best
model to use in production for classifying new unseen song as Like and Dislike.
• Logistic regression
• K-Nearest Neighbors (KNN)
• Random Forests, Bagging
• Boosting
• Support Vector Machines (SVMs)

The task is to classify a test dataset of 200 songs which contains a high-level audio
features extracted using Spotify web-API. These features describe characteristics for
classifying new songs such energy, danceability, valence, tempo etc. First we start
with trying out different classification methods in order to find the best algorithm
with highest accuracy.
Tools:
• Training data set with 750 songs classified as like (1) and dislike (0).
• Seaborn, matplotlib, pandas and numpy for data visualization and analyzing
• Sklearn to build the machine learning models
