# Overview

LIRI-Bot is a command line node based application that was built to interpret pre-defined parameters and translate them into node based data requests. 

# Pre-defined parameters:
  1) node liri.js my-tweets
  2) node liri.js spotify-this-song "a song"
  3) node liri.js movie-this "a movie"
  4) node liri.js do-what-it-says

### node liri.js my-tweets
This command is interpreted as an encrypted, user-athethenticated function call to twitter API through the npm, twitter.  This function retrieves the last 20 tweets of my twitter account and displays them in the terminal
 
### node liri.js spotify-this-song "a song"
This command is interpreted as a function call to spotify API through the npm, spotify. This function retrieves a number of details about each artist that has performed this song and displays them in the terminal
 
### node liri.js movie-this "a movie"
This command is interpreted as a function call to OMDB API through the npm, require. This function retrieves a number of details about the specified movie and displays them in the terminal

### node liri.js do-what-it-says
This command is interpreted as a function call to read the "random.txt" file through the fs package and interpret its contents to call one of the previously mentioned functions to either retrieve tweets, song information, or movie information and display them in the terminal.


