# actor_data_feature
Data feature and purpose:
The data feature is actor names and the movies that they are known for from the TMDB API and using the actor names to fetch news on the actor from the NYTimes API.
The purpose is to find more movies from the actor and to get the latest actor news.

APIs used:
TMDB - Has information on actors and movies
NYTimes - Has information on news
They are chosen because they contained most of the information wanted.

Instructions:
Run:
For news:
ticker = input("Enter an actor name ticker symbol: ")
news = get_news_for_ticker(ticker)
display_news(news)

For movies:
ticker = input("Enter an actor name ticker symbol: ")
movies = get_movies_for_ticker(ticker)
display_movies(movies)

Prerequisites: TMDB and NYTimes API keys
