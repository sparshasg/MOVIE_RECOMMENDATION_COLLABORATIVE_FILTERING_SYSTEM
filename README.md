# MOVIE_RECOMMENDATION_COLLABORATIVE_FILTERING_SYSTEM
<i>A machine learning project done under the guidance of DLithe Company.</i>
</br><b>DLithe Internship Certification Program</b>
</br><b>Project Topic: </b>
MOVIE RECOMMENDATION COLLABORATIVE FILTERING SYSTEM
</br><b>Reference:</b>
Dlithe
</br><b>Website: </b>
www.dlithe.com
</br><b>Project done under the guidance of: </b>
Dlithe
</br><b>Done by: </b>
Sparsha S G 1AT17CS086</br></br>
<b>Movie Recommendation Collaborative Filtering System using Machiene Learning</b>
</br>This system offers a generalized prediction to make personal movie recommendations based on each individual's unique tastes.This model uses the Movies metadata 
collected from TMDB to come up with Top movie rated list and this also recommends based on movie ratings, movie popularity and directors.
</br></br><b>Use of Files :</b>
</br><i>User Ids:</i>
MovieLens users were selected at random for inclusion. Their ids have been anonymized.
</br><i>Movie Ids:</i> Movie ids are consistent between `ratings.csv`, `movie_data_chart.csv`, and `links.csv`.
</br><i>Ratings Data File Structure (ratings.csv):  </i>All ratings are contained in the file `ratings.csv`. Its format: userId,movieId,rating,timestamp.
 The lines within this file are ordered first by userId, then, within user, by movieId.
 </br><i>Movies Data File Structure (movie_data_chart.csv):  </i>Movie information is contained in the file `movie_data_chart.csv`.
Genres are a pipe-separated list, and are selected from the following:

* Action
* Adventure
* Animation
* Children's
* Comedy
* Crime
* Documentary
* Drama
* Fantasy
* Film-Noir
* Horror
* Musical
* Mystery
* Romance
* Sci-Fi
* Thriller
* War
* Western
* (no genres listed)
</br><i>Links Data File Structure (links.csv):  </i>
Identifiers that can be used to link to other sources of movie data are contained in the file `links.csv`. Its format:
movieId,imdbId,tmdbId.
</br><i>credits Data File Structure(credits.csv): </i>credits information is contained in the file `credits.csv`. Its format:cast,crew,id.
</br><i>keyword Data File Structure(keyword.csv): </i>keywords information is contained in the file `keywords.csv`.Its format: id,keyword.
</br></br><b>Algorithm used: </b>
</br><i>Pearson Similarity:</i> The Pearson Similarity procedure computes similarity between all pairs of movies.
</br><i>Cosine Similarity :</i> The Cosine Similarity procedure is used to calculate a numeric quantity that denotes the similarity between two movies.
</br><i>Collaborative Filteringbr><i> algorithm:</i> This algorithm recommends the most similar items to the user by calculating the similarity between the movies.
</br></br><b>The types of Recommender Used:<b>
  </br><i>General Movie Recommender:</i> This model recommends the movies that are more popular.
   </br><i>Content Based Recommender:</i> This model recommends based on movie Taglines, Overviews and cast.
   </br><i>Movie Description Based Recommender:</i> this model recommends using movie description and tagline.
  </br><i>Metadata Based Recommender:</i> This model uses the crew informationof the movie data and the keyword to recommend the movie.
  </br><i>Rating Based Recommender:</i> This model recommends the movie based on the user ratings.
  </br><i>Similarity Based Recommender:</i>This model gives the personalised recommendation of the similar movies with highest ratings.
  </br><i>Collaborative Filtering Recommender:</i>

