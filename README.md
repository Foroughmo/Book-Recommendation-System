# Book-Recommendation-System
Developing a personalized book recommender using machine learning

Main objective of this project is focused on developing a recommender system that uses user ratings and preferences to deliver personalized book recommendations. The process includes an initial exploratory analysis to understand user and book data, followed by the application of collaborative filtering, content-based recommendation system and deep learning techniques to predict user preferences. The models' effectiveness will be  evaluated and improved through regularization techniques.

## Data Preprocess

## Popularity Based Recommender 

  Popularity based recommendation systems are based on the rating of items by all the users.

  Most popular books across the dataset is represented below based on average rating.


## User_Based Recommender

  Created a matrix that rows are representing user-ID’s and columns are representing book titles
  
  Similarity matrix based on cosine similarity was then calculated


## Item_Based Recommender 

  ### Feature Engineering

  Based on subject matter expertise the following features were selected for the item-based system: 
  User_Ids: Specifying users who have provided more than 200 reviews(knowledgeable users)
  Books: Creating a list of famous books, books that have more than 10 counts of ratings
  Filtering the data and creating matrix with rows of book titles and columns of user ids
  Calculating cosine similarity


## Content_Based Recommender
Using LLM 

  Using a large language model, I generated a short one-sentence description for each book title and stored the sentences in the data frame 
  Due to tokens limits of the LLM ( Chat-GPT 4.0 used in this case) I selected a sample of 100 book titles
  Text processing and feature extraction was performed by using TfidfVectorizer and ntlk library: 


## Results
## Future Consideration 
