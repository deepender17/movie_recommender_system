![222](https://user-images.githubusercontent.com/76167270/236693335-ebb5df53-2d30-4188-812b-12e28a5cbb87.png)

# Movie Recommender System


The movie recommendation system is a Python , machine learning application that uses Flask for deployment. It allows users to receive personalized movie recommendations based on their preferences and viewing history. The system employs collaborative filtering algorithms to analyze user data and generate accurate recommendations. The user interface is designed to be user-friendly and intuitive, with simple inputs for user preferences and a visually pleasing display of movie recommendations. By utilizing machine learning techniques and Flask for deployment, this recommendation system is an efficient and effective way to enhance the movie viewing experience for users.
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

![11111](https://user-images.githubusercontent.com/76167270/236693409-46018082-d7ef-4970-9061-ee3296d974c0.png)

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.
