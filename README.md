# Movie-Recommendation-System-using-python
<b><b>The followings are dataset explaination:-</b></b><br>
index--index of tghe movie(S.No.)<br>
budget--amount of money spent on making this movie<br>	
genres--the genre of the given movie<br>
homepage--homepage site of that movie	<br>
id	<br>
keywords--keyword that can be used to search that movie on OTT platform. The given movie is basded on these keywords<br>	
original_language--the language the movie was made<br>
original_title--original name of the movie	<br>
overview--short summary of the movie	<br>
popularity--popularity score	<br>
production_companies--compant that produced this movie	<br>
production_countries--the country in which that movie was produced	<br>
release_date--date on which the movie was released	<br>
revenue--the overall amount of money that movie made 	<br>
runtime--lenght of the movie	<br>
spoken_languages--languages spken by cast in that movie	<br>
status--whether the movie is released or not, whether its still in rumor to be made and so on<br> 	
tagline--tagline which defines that movie. Generally comes at the statrting of the movie	<br>
title--name of the movie	<br>
vote_average--average of the vote earned by movie from audience	<br>
vote_count--total couont of the vote earned by movie from audience<br>
cast--actors and actresses in that movie	<br>
crew--members that were involved in making of that movie(like director, makeup team, stuntman and so on)<br>	
director--person that directed that whole movie<br>
<br>
<b><b>ML Operations:-</b></b><br>
1.imported basic python libraries and modules like numpy and pandas along with Tfidfvectorizor to convert textual data to numerical vector <br>
2.basic exploratory data analysis<br>
3.random feature selection(chose feature that i felt important can also use operations like featurewiz,boruta, sequentialfeatureselector,etc.. to select ideal features)<br>
4.filled nulled values in those selected column<br>
5.combine those selected features into one single column<br>
6.used Tfidfvectorizor to convert textual data to numerical vector<br>
7.similarity scores using cosine similarity<br>
8.used dfflib Python module to get close match between entered movie name and the movie the dataset
9.used python to generate codes to get name of similar movies based on the index
