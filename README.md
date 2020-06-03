# books-recommendation-system

Contents:
 - [Introduction](#Introduction)
 - [ Project Title](#Project_Title)
 - [Problem Statement](#Problem-Statement)
 - [Dataset Description](#Dataset-Description)
 - [Data Cleaning](#Data-Cleaning)
 - [Modeling using KNN](#Modeling-using-KNN)
 - [Challenges](#Challenges) 
 - [Future Work](#Future-Work)
 
 #### Introduction
Recommender Systems, is an information filtering technology, to make predictions on user preferences and make recommendations which should interest customers.
It's utilized in a variety of areas and are most commonly recognized as playlist generators for video and music services like YouTube and Spotify, product recommenders for services such as Amazon.
#### Project Title
Books Recommendation System.

#### Problem Statement
Building collaborative recommender system that's aggregate ratings  of books, recognize commonalities between the users on the basis of their ratings, and generate new recommendations based on comparisons between users.

#### Datasets Description
Book-Crossing Dataset from the Book-Crossing community which contains 278,858 users, 1,149,780 ratings, about 271,379 books.

#### Data Cleaning
This part of the project focuses on iteration through the dataset, removing null values, converting features to the right data type, and fixing wrong entry for some features.

#### Modeling 
To implement an item based collaborative filtering, K-Nearest Neighbors is the perfect algorithm it will calculate the distance between the target book and every other books in its database. It then ranks its distances and returns the top k nearest neighbor books as the most similar book recommendations.

#### Challenges
- Changing data 
- Lack of features 
- Wrong entries 

#### Future Work
- Datasets
- Neural Network
- Flask 
