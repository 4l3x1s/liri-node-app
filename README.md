# liri-node-app

Authors: Alexis Corrieras
Date: March 27th, 2019
License: MIT License


##1 What the project does:

#  Overview:

In this assignment, you made LIRI. LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

#  Before You Begin:

LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.

The  `Commands` are:

   * `concert-this`
   * `spotify-this-song`
   * `movie-this`
   * `do-what-it-says`


#2 How users can get started with the project:
#  Video:

Watch the video here: https://drive.google.com/file/d/1Z3nGUXjANWhNy27zerWiOllZIG_AET7D/view

#  Instructions:

1. Open the terminal (Git Bash).
2. Navigate to the folder that contains the `liri.js` file. 
3. Run one of the command.

    **Command 1**: Run the `concert-this` command
    
        node liri.js concert-this <name of artist or band>
    
    Output: The system will display a list of all events and locations where the artist or band will perform. It can result in multiple records. The system will also log all the results in the log.txt file. See screenshot below:

    [Screenshot](/concert-this.JPG)

    **Command 2**: Run the `spotify-this-song` command
    
        node liri.js spotify-this-song <name of song>
    
    Output: The system will display a list of information associated with the song. It can result in multiple records. The system will also log all the results in the log.txt file. See screenshot below:

    [Screenshot](/spotify-this-song.JPG)

    **Command 3**: Run the `movie-this` command
    
        node liri.js movie-this <name of movie>
    
    Output: The system will display information associated with the movie. The system will also log all the results in the log.txt file. See screenshot below:

    [Screenshot](/movie-this.JPG)


    **Command 4**: Run the `do-what-it-says` command
        
        node liri.js do-what-it-says
        
    Output: The system will read the text in the random.txt file, and perform the command written in the file. 
    
    See screenshot below:

    [Screenshot](/do-what-it-says.JPG)



#3 Technologies used:
* Javascript
* Node.js
* Node packages:
    * Node-Spotify-API
    * Axios
    * Moment
    * DotEnv
* APIs used:
    * Bands in Town
    * OMDB
