# Movie-Recommendation-System-using-python
The followings are dataset explaination:-<br>
index--index of tghe movie(S.No.)<br>
budget--amount of money spent on making this movie<br>	
genres--the genre of the given movie<br>
homepage--homepage site of that movie	<br>
id	<br>
keywords--keyword that can be used to search that movie on OTT platform. The given movie is basded on these keywords	
original_language--the language the movie was made
original_title--original name of the movie	
overview--short summary of the movie	
popularity--popularity score	
production_companies--compant that produced this movie	
production_countries--the country in which that movie was produced	
release_date--date on which the movie was released	
revenue--the overall amount of money that movie made 	
runtime--lenght of the movie	
spoken_languages--languages spken by cast in that movie	
status--whether the movie is released or not, whether its still in rumor to be made and so on 	
tagline--tagline which defines that movie. Generally comes at the statrting of the movie	
title--name of the movie	
vote_average--average of the vote earned by movie from audience	
vote_count--total couont of the vote earned by movie from audience
cast--actors and actresses in that movie	
crew--members that were involved in making of that movie(like director, makeup team, stuntman and so on)	
director--person that directed that whole movie

ML Operations:-
1.imported basic python libraries and modules like numpy and pandas along with Tfidfvectorizor to convert textual data to numerical vector 
2.basic exploratory data analysis
3.random feature selection(chose feature that i felt important can also use operations like featurewiz,boruta, sequentialfeatureselector,etc.. to select ideal features)
4.filled nulled values in those selected column
5.combine those selected features into one single column
6.used Tfidfvectorizor to convert textual data to numerical vector
7.similarity scores using cosine similarity
8.used dfflib Python module to get close match between entered movie name and the movie the dataset
9.used python to generate codes to get name of similar movies based on the index
