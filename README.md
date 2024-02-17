# Book_Recommendation_System
Welcome to our Book Recommendation System! This system provides personalized book recommendations based on user preferences and past interactions. Whether you're an avid reader looking for your next favorite book or a casual reader exploring new genres, our recommendation system has got you covered.

### Project Summery
During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.
In a very general way, recommender systems are algorithms aimed at suggesting relevant.
Items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries). Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

### Problem Statement

Need to built a Recommender System for books. Whith the help of this system any website can recommend the books to their user accound to the behaviour of the user. Like,

  * Book which the most likily to read
  * Books based on the geners which is mostely read

Which macke the user experiance better and help the website to grow more.

### About Data
Data have three seprate file Books, Users, Ratings.

  * Books Dataset contain information about books such as booksname, ISBN number, author, image url etc.
  * Users dataset contain the information about users who read or bought the books like their ID, Age, Location.
  * Ratings Dataset contain information about the ratings given by the readers to a book like userID, ISBN, Ratings.

### Model Used

  * Popularity based recommendation System
  * Collaborative filtering based recommendation System
  * Clustring based recommendation System

### Conclusion

At first we found large number of null value found in Users dataset['Age'] column but when we move forword we found that their is no need for this dataset to build out model. So, their is no need for impution of these null values.

We do some Transformation like lower case for all column name and remove unnessesary column so that we can used the in analysis.

We develop three model for the perticular problem like,

Popularity based recommendation System
Collaborative filtering based recommendation System
Clustring based recommendation System
from all above recomender system we found collaborative filtering is the best suited.

We recommended 5 books to each reader so that he/she can read qulity content and the content which they like the most.
