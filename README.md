# LiriBot
A language Interpretation and Recognition Interface that uses command line in node to retrieve and give you back data
* LIRI will search Spotify for songs, Bands in Town for concerts and OMDB for movies

## How to use LIRI
* LIRI is able to take in 4 commands utilizing node.js
    * concert-this
    * spotify-this-song
    * movie-this
    * do-what-it-says

## What each command does
example: node liri.js concert-this <band or artist name>
```
1. 'node liri.js concert-this \<band or artist name\>'
    * Displays a list of results of where the band or artist is performing  
    
    ![concert-this command](https://user-images.githubusercontent.com/41643506/50050526-6be05f00-00c3-11e9-934f-297eba139d12.png)
```
example: node liri.js spotify-this-song Mr Brightside
```

2. 'node liri.js spotify-this-song \<song name\>'
    * Displays the top 3 results of the song name
    
    

```
example: node liri.js movie-this The Avengers
```

3. 'node liri.js movie-this \<movie title\>'
    * Displays the following information
        * Title of the movie
        * Year of the movie
        * IMDB Rating of the movie if available
        * Rotten Tomatoes Rating of the movie if available
        * Where was the movie produced
        * Language of the movie
        * Plot of the movie
        * Actors in the movie
    * If there is no movie title inserted, the search will default to Mr. Nobody

    * something special happens if you come across a movie that was produced in a certain country....

```
example: node liri.js do-what-it-says
```

4. 'node liri.js do-what-it-says'
    * Takes the text from random.txt and runs the song through the spotify-this-song command

   ![do-what-it-says command](https://user-images.githubusercontent.com/41643506/50050535-9a5e3a00-00c3-11e9-8095-8337103fa33d.png)

* In addition to logging out your results to the terminal, it will log out your inputs and results in a log.txt file!


## Built With
* [Node.js](https://nodejs.org/en/)
* [Spotify NPM Package](https://www.npmjs.com/package/node-spotify-api)
* [colors NPM Package](https://www.npmjs.com/package/colors)
* [request NPM Package](https://www.npmjs.com/package/request)
* [moment NPM Package](https://www.npmjs.com/package/moment)

## Author

* **John Plattenburg Jr.**  
