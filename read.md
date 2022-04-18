## OVERVIEW
* After delivering and contributing a lot in tech world, microsoft wants to jump into the entertainment industry. In order to successfully lanch their first feature film, the comapny decided to analyse data. this data belongs to IMDB and contain all necessary information regarding movie credentials. The project aims to analyse the data after cleaning and sorting. and then to make specific recommendation.
## METHODS
* to perform this analyzation, we used data from IMDB.
* open source librarries are used such as pandas, matplot lib, sns to demonstrate this data and resuts.
## Step-by-step guide to the code for the project
## importing
* importing libraries
* we imported open source libraries to work with.
* these libraries will help to clean and sort data and then to present in graphical way.
* importing data. 
* we are using four different datasets from different sources. 
* these datasets are the collection of records about all details of movies in past couple of years.
## cleaning
* first, we imported inital data and performed some comands to look what is in there.
* for this, we used comands like .describe(), .head(). .tail(), .shape, .duplicate
* then we cleaned the columns and sorted the data.
* for this, we used comands such as .remove()
* now, we merged two data sets in order to get a broad picture.
* we used .merge function for this.
## analysing
* for analyation, we seeked for the variables such as famous director, writer, average rating, runtime etc.
* first, we check the average rating. this rating affects the popularity and metascore of movie.
* then, we checked and came to the conclusion that, runtime should be between 100 to 110 minutes.
* various graphs are created the show the relation between certain variables.
