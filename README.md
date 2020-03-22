# Recommendations-with-IBM
This is No.5 project in Data Scientist Nano Degree program @ UDACITY.

# Introduction
For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like.   
This project will be divided into the following tasks.

### I. Exploratory Data Analysis  

Before making recommendations of any kind, I explored the data that I was working with for the project. There are some basic, required questions to be answered about the data.  

### II. Rank Based Recommendations  

To get started in building recommendations, I first found the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, I looked at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

### IV. Matrix Factorization

Finally, I complete a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I can get an idea of how well I can predict new articles an individual might interact with.

# Jupyter Notebook
[Recommendations_with_IBM.ipynb](https://github.com/Data-Semi/Recommendations-with-IBM/blob/master/Recommendations_with_IBM.ipynb)
