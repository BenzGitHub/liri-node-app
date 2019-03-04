**LIRI Bot**

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.

**concert-this**

This will search the Bands in Town Artist Events API for an artist and render the following information about each event to the terminal:

Name of the venue
Venue location
Date of the Event

Bands with two words such as Imagine Dragons, should be entered as one word with no spaces
Example: node liri.js concert-this imaginedragons

**spotify-this-song**

This will show the following information about the song in your terminal/bash window:
Artist(s)
The song's name
A preview link of the song from Spotify (if available)
The album that the song is from

If no song is provided then the program will default to "The Sign" by Ace of Base.


Songs with more than word such as Whatever it Takes, should be entered with dashes instead of spaces.
Example: node liri.js spotify-this-song whatever-it-takes

**movie-this**
This will output the following information to your terminal/bash window:
Title of the movie
Year the movie came out
IMDB Rating of the movie
Rotten Tomatoes Rating of the movie
Country where the movie was produced
Language of the movie
Plot of the movie
Actors in the movie


If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'


Movies with more than one word such as Independence Day, should be entered with dashes instead of spaces
Ex. node liri.js movie-this independence-day

**do-what-it-says**

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.

It should run spotify-this-song for "I Want it That Way," as follows the text in random.txt.


