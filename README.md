# LiriBot
A language Interpretation and Recognition Interface that uses command line in node to retrieve and give you back data
* LIRI will search Spotify for songs, Bands in Town for concerts and OMDB for movies

## How to use LIRI
* LIRI is able to take in 4 commands utilizing node.js
    * concert-this
    * spotify-this-song
    * movie-this
    * do-what-it-says

## How to use LIRI
* LIRI is able to take in 4 commands utilizing node.js
    * concert-this
    * spotify-this-song
    * movie-this
    * do-what-it-says

## What each command does
  ![concert-this command](https://user-images.githubusercontent.com/41643506/50050588-36d50c00-00c5-11e9-9941-75851fc9ef32.png)<br>
  ```
example: node liri.js concert-this <band or artist name>
```
1. 'node liri.js concert-this \<band or artist name\>'
    * Displays a list of results of where the band or artist is performing  

![spotify-this-song command](https://user-images.githubusercontent.com/41643506/50050592-3f2d4700-00c5-11e9-8d3b-bb74c4f5392f.png)
<br>
```
example: node liri.js spotify-this-song Mr Brightside
```

2. 'node liri.js spotify-this-song \<song name\>'
    * Displays the top 3 results of the song name

![movie-this command](https://user-images.githubusercontent.com/41643506/50050591-3ccaed00-00c5-11e9-9073-73d39ac8abf4.png)<br>
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

![do-what-it-says command](https://user-images.githubusercontent.com/41643506/50050589-3a689300-00c5-11e9-848e-5ea1cb594557.png)
<br>
```
example: node liri.js do-what-it-says
```

4. 'node liri.js do-what-it-says'
    * Takes the text from random.txt and runs the song through the spotify-this-song command


* In addition to logging out your results to the terminal, it will log out your inputs and results in a log.txt file!


## Built With
* [Node.js](https://nodejs.org/en/)
* [Spotify NPM Package](https://www.npmjs.com/package/node-spotify-api)
* [colors NPM Package](https://www.npmjs.com/package/colors)
* [request NPM Package](https://www.npmjs.com/package/request)
* [moment NPM Package](https://www.npmjs.com/package/moment)

## Author

* **John Plattenburg Jr.** 

