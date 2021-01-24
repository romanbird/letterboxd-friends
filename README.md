# letterboxd-friends: Generate a top-chart based on your friends' ratings.

Find the movies, with the highest average rating from your Letterboxd friends.

The code is written for Python 3.8.1 and requires the modules: 'Requests', 'BeautifulSoup' and 'lxml'.

The programm takes your Letterboxd username and searches all users you are following. You have also the choice to to select just some special users.
All rated movies of the given users are collected and an IMDB style Bayesian estimate for every movie is computed. You have the option to exclude the movies you watched.

The results can be filtered for the number of ratings per movie.
Finally the list is saved as csv in the same directioiry as this code.
