
# **Building And Deploying A Netflix Recommender System**

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API. 

We use *web scraping* to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
## Running Flask Tests

To run a Flask deployment tests, run the following command

```bash
  python main.py
```


## Running Heroku Tests

To run a Amazon aws deployment tests, click on the following link:

[Netflix Recommender System App](http://ec2-13-211-39-16.ap-southeast-2.compute.amazonaws.com:8080/)


## Deployment

### Steps To Deploy The App:

Prepare your dataset:

        1. Data Extraction
        2. Exploratory Data Analysis(EDA)
        3. Feature Engineering
        4. Model Building and Tuning
        5. Building Flask API
        6. Pushing code to Github
        7. Connecting to Amazon aws  
        8. Deploy App


## Demo

[Click HERE To View App](http://ec2-13-211-39-16.ap-southeast-2.compute.amazonaws.com:8080/)





<img width="948" alt="netflixss" src="https://github.com/VijayRajIITP/Netflix---Recommender-System1/assets/149241319/bcb2f825-343e-4a4f-9527-67f2ae9df14b">





