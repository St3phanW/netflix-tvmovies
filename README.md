# netflix-tvmovies


In this project, I am tasked with answering a few leading questions for Netflix. 
1. What type of shows/movies should we invest in?
2. What shows/movies appeal to different age groups?
3. How has the quality of Netflix shows/movies evolved over time? Are there shifts in audience preferences or industry standards?

We have the following columns:

title              :  The name of a TV show or movie. (Text)
type               :  Indicates whether an entry is a TV show or a movie. (Text)
description        :  A brief summary or description of a TV show or movie. (Text)
release_year       :	The year in which a TV show or movie was released. (Numeric)
age_certification  :  The age certification rating for a TV show or movie. (Text)
runtime            :  The length of an episode for TV shows or duration of a movie. (Text)
imdb_score         :  The score given by users on IMDB for a particular title. (Numeric)
imdb_votes         :  The number of votes received by each title on IMDB. (Numeric)



Cleanup:
We format column J to numerical. There are two types of wrong input values. 
We have a few wrong values. 8,199,999,999,99. Same with 8,699,999,999,999. We change these to 8.2 and 8.7 respectively
