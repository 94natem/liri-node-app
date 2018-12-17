# liri-node-app

The app will allow you to run 4 functions. 
Spotify-this: When you specify a song after calling this function it will attempt to pull all the details from the spotify api.
node liri.js spotify-this "Pretender"

Concert-this: When you specify a band or an artist after calling this function it will pull upcoming concerts from the bandsintown api.
node liri.js concert-this "Foo Fighters"

Movie-this: When you specify a movie after calling the function it will pull all the details from the omdb api.
node liri.js movie-this "Die Hard"

Do-what-it-says: This function will read the text file and pull the call specified within. For example I run the spotify-this function in my text file for a backstreet boys song.
node liri.js do-what-it-says

Concert-this being run.
![picture](images/Concert.png)

The default movie being pulled up when the specified movie can't be found.
![picture](images/Defaultmovie.png)

The default song pulled up when the specified song can't be found.
![picture](images/Defaultspotify.png)

The movie specified by the movie-this call being displayed with details.
![picture](images/Movie.png)

The song specified by the spotify-this call being displayed with details.
![picture](images/Spotify.png)

Pull the command from a text file to use the call in the app.
![picture](images/Text.png)
