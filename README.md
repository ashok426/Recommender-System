# Recommender-System
Book Recommendation Using **Word2vec algorithm**

Content-based and Collaborative based are the two popular recommendation systems. In this project, I have applied content based recommender system.

# Content-based recommendation system

A content-based recommendation system recommends items to a user by taking similarity of items. This recommender system recommends products or items based on the description or features.

## Demo:

Let's have a look on my web application which gives book recommendation based on user favourite book. Select the below link..

[https://recommenbook3.herokuapp.com/]

In the dropdown list of web app, there were around 4000 books and user has to select one book title from a list of 4000 books, then recommender system list top 5 similar books

![Capture](https://user-images.githubusercontent.com/63462922/143883296-7b024024-3de8-4a09-8fd4-bab830e72cd6.PNG)

# About this project:

This project, I have used goodreads scraped dataset which contains around 4000 book titles, author name and description of each book and author.

After text preprocessing, the main thing is to convert each book descriptions into numerical vectors. For this we have used 3 method such as **Bag-of-words model, TF-IDF model, Word2vec algorithm**. From the above method, Word2vec model was an best one.

Word2vec is an neural network model uses **semantic meaning of words**. Word2vec understand the semantic meaning of each words in the book description feature very well than the other two models such as bag of words and tf-idf. 

Training word2vec algorithm from scratch is an computationally expensive and also need humonguous data. As i have less data, so i have used **Google pretrained word2vec neural network** for this project. 

