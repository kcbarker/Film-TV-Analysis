# TV and Film Analysis from Netflix Data 

Carrying out Excel, SQL and Python analysis on Netflix Data obtained from Kaggle: https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies and then experimenting with visuals from this data on Power BI and also using matplotlib. 

Cleaning and exploring data to ascertain the most popular titles and genres. 

Excel: 

* Used the titles.csv file and deleted rows that I was not interested in analysing (age certification, run time, release year). I checked for duplicates (there were none), and filted for blanks and removed any rows that had blank information. I sorted the imdb score data to check for any anomalies (i.e. any values above 10). 
* Created a new file using filters to show the Top 10 movies (excluding TV shows) based on imdb score and produced a bar chart showing this data. 
* Imported credits data as a second sheet as used VLOOKUP function to show the imdb score from sheet 1 against the character information in the credits sheet
* Used COUNTIF function to calculate count of type (i.e. the number of movies and the number of shows in the data)
* Used pivot tables to show the total number of movies and tv shows on Netflix and also each title against the IMDB score.
* Created a visualisation to show the Top 10 Movies on Netflix 

SQL: 

* Imported the titles_blanks_and_unwanted_columns_removed.csv file into MySQL workbench and carried out analysis there - shown in my comments in the .sql files.
* Querying the data to show the top 10 movies, top 10 shows, top 10 titles by various genres, and exploring the most popular genres. 

Power BI:

* Created a visualisation to show the spread of imdb scores and which scores most titles tend to fall within
* Created a visualisation to show which country most titles on Netflix come from - the most common being the USA. 

Python:

* Carried out in Jupyter Notebooks
* Importing and exploring data using pandas
* Cleaning data by dropping unwanted column
* Exploring data to:
  - ascertain most common imdb scores for Netflix titles to give an indication of the quality of titles on there and how likely users are to like the titles on the platform
  - exploring the number of each type of genre on Netflix to explore the spread of genres on the platform
  - exploring the titles with the highest imdb scores, and also most with the highest imdb scores released since 2010, to ascertain which titles should be the most popular based on imdb score - if we had the data of which     titles are most streamed, it would be interesting to explore the correlation between imdb scores and most streamed to see if the two are related and whether imdb score could be used as a predictor of the success of        titles on the platform
  * Creating a function to define titles as excellent, good or poor depending on their imdb score
  * Using matplotlib to explore whether there is a correlation between runtime and imdb score to consider whether a film's length impacts on how popular it is with viewers - there was no correlation
  * Using matplotlib to show the spread of imdb scores for Netflix titles - useful to consider whether high quality titles are being included on the platform. 
  
Ideas for further analysis: 
* Obtain data for other streaming platforms and consider which platform has the most highly rated shows and movies available.
* Obtain data for which are the most streamed titles on Netflix and consider whether imdb score is a good predictor of success on the platform. 

