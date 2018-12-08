# LIRI APP

LIRI is a Language Interpretation and Recognition Interface - a command line node app that takes in parameters and gives you back data. Liri is a node app that utilizes Spotify, omdbAPI, bandsintownAPI.

## Examples

**Insert artist name to find upcoming event(s) regarding the artist**
![concert-this]
(/images/concert-this.png)

**Insert song title to find information regarding the song**
![spotify-this-song]
(/images/spotify-this.png)

**Insert movie title to find information regarding the movie**
![movie-this]
(/images/movie-this.png)

**Takes text from random.txt and then call the function**
![do-what-it-says]
(/images/do-what-it-says.png)

# How it works

To retrieve the data that will power this app, we send requests using the axios package to the Bands in Town, Spotify and OMDB APIs. Node packages that are crucial for this app.

* Node-Spotify-API
* Axios
* Moment
* DotEnv
