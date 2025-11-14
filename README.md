# AI Sentiment Analysis
This is a university project I made. It contains 3 ways to recognise sentiment, Naive Bayes, Logistic Regression with Stochastic Gradient Descent and a Stacked Bidirectional RNN with LSTM cells. In this project, they are used to determine if a movie review is positive or negative. They are all trained and tested using IMDB's database.

# Requirements
Python and libraries like pandas, pytorch and cuda are needed. Numpy is optional but you should always use it. I will explain below.

# Important Details
All will run. The issue is that the Logistic Regression was not made using sparse matrices from numpy so it runs incredibly slow. You can see the difference by running Naive Bayes, which uses them. You can always try to change things up and fix this issue. Also for cude you need to set things up yourself. This was left out because i didnt have the hardware necessary.

# Ranking
Top will always be the RNN. Second i would say Naive Bayes although it is hard to tell the difference between its results and Logistic Regression's.

# Recommendations
Always use the RNN. You can always play around and make it predict other things + it is also more fun in my opinion.
