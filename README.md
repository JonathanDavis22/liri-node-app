# Liri-Node-App

A Siri-style JavaScript/Node application.

## Getting Started

Using Node and your Liri application, search Spotify for a song, Bands In Town for if a musical artist or group is playing in your city
soon, or OMDB for information about any movie you might be curious about.

### Prerequisites

Node, Moment, Axios, Request.

### Installing

Download the repository. Create a .env file with your individual API keys. Open your terminal and run the Liri JavaScript file in Node.

### Use

## Spotify

Use the command "spotify-this-song" and then the song title in quotations in order to search songs. Sometimes including more information, 
such as the band name, helps clean up results. No quotations are needed for one-word song titles.

# Results

The artist name, song title, and album the song appeared on will be displayed to the user. If available, a preview of the song will also 
appear, including a link to listen to that preview.

![Spotify search](https://github.com/JonathanDavis22/liri-node-app/blob/master/Screenshots/Spotify.png?raw=true "Spotify Search")

![Spotify search](https://raw.githubusercontent.com/JonathanDavis22/liri-node-app/master/Screenshots/Spotify%202.png "Spotify Search")

## OMDB

Use the command "movie-this" followed by the movie title in quotations in order to search movies. No quotations are needed for one-word 
films titles.

# Results

The movie title, release date, ratings, county of production, language(s), plot, and main cast of the searched film will be returned to
the user.

![OMDB search](https://raw.githubusercontent.com/JonathanDavis22/liri-node-app/master/Screenshots/OMDB.png "OMDB Search")

## Bands In Town

Use the command "concert-this" followed by the name of the band in quotes you wish to search in order to see if they have any upcoming 
concerts. No quotations are needed for one-word band names.

# Results

The venue name, venue location, and date of the show will be returned to the user.

![Bands In Town search](https://raw.githubusercontent.com/JonathanDavis22/liri-node-app/master/Screenshots/BandsInTown.png "BIT Search")

## Built With

* [Node](https://nodejs.org/api/http.html) - The JavaScript runtime used
* [Spotify API](https://developer.spotify.com/documentation/web-api/) - Used to search songs
* [OMDB API](http://www.omdbapi.com/) - Used to search movies
* [Bands In Town](https://manager.bandsintown.com/support/bandsintown-api) - Used to search bands in town

## Authors

* **Jonathan Davis** - *Completion* - (https://github.com/JonathanDavis22)
* **Mac Hollister** - *Initial work, tutoring* - (https://github.com/macdhollister)
