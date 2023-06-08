# WishlistOnTv
Whats on TV from my wishlist

# Goal

Display me a list (movie name, rating on IMDB, poster, actor names, type, synopsis) of movies that will go in TV today on my local TV stations.
Preferably display movies in my Wishlist
Then movies that I have seen and marked them as 8+ stars
Then movies that I have not see and have high scores on IMDB / CSFD

## Getting User's wishlist
* IMDB does not have such API
* other 3rd party projects do not offer it either
* StackOverflow answers suggest logging in the browser, passing cookies to python script
* or download data manually

## Getting IMDB movie data
* python package cinemagoer (formerly imdbpy) provides info about movies, ratings
* http://www.omdbapi.com offers API, probably scraped IMDB
* https://stackoverflow.com/questions/1966503/does-imdb-provide-an-api

## Getting CSFD movie data

## Getting TV program data

* xmltv sounds good, but for SK/EU it says:
  * The tv_grab_eu_epgdata(1) grabber is a XMLTV grabber for the commercial www.epgdata.com service. Currently, you get a full year of EPG listings for EUR 17.95.
  *
