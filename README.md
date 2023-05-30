# Book_Recommender_System
## What?
- Recommender systems are systems that are designed to recommend things to the user based on many different factors. These systems predict the most likely product that the users are most likely to purchase and are of interest to.
- Companies like Netflix, Amazon, Instagram etc. use recommender systems to help their users to identify the correct product or movie for them.

## Why?
- Increase in revenue based on personalization.
- Better user experience.
- More time spent on the platform.
- Help websites improve user engagement.

## Applications?
- Netflix to recommend movies
- E-commerce websites to recommend the products
- Social media platforms to recommend feeds/blogs/news/songs....etc. Ex: Instagram, Facebook
- Food recommendations by Zomato, Swiggy.
- Songs recommendations by Spotify.
- Dating apps recommending people.

## Types?
- Popularity-based recommender system
- Content-based filtering system
- Collaborative-based filtering system

## Objective: To provide personalized book recommendations to users based on the behaviour and preferences of other users
who have similar tastes and interests.
- Collected and analyzed data on book genres, authors, and user ratings and performed EDA
- Implemented collaborative filtering technique to analyze user behaviour patterns to identify similarities in their
preferences and recommend books that other similar users have enjoyed.
- Considering only those users who have rated more than 200 books and only those books that have received more than 50 ratings.(This step helped in reducing the noise and sparsity in the data by focusing on users and books that have a significant number of ratings.)
- Next, calculated the similarity scores between the books using the cosine similarity measure.
- This approach calculates the distance between the ratings of two books, which helps in identifying the books that are similar in terms of their ratings. Finally, based on the similarity scores, generated recommendations for a selected book. By considering the books with the highest similarity scores to the selected book, were able to recommend other books that users with similar tastes might also enjoy.
- Successfully deployed the model using the Flask framework on to a cloud platform(Render).
