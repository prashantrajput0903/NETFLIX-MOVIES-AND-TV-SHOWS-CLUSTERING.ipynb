# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flexible which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

#Data Description
show_id: Unique ID for every Movie / Tv Show

type: Identifier - A Movie or TV Show

title: Title of the Movie / Tv Show

director: Director of the Movie

cast: Actors involved in the movie/show

country: The country where the movie/show was produced

date_added: Date it was added on Netflix

release_year: Actual Releaseyear of the movie/show

rating: TV Rating of the movie/show

duration: Total Duration - in minutes or number of seasons

listed_in : Genre

description: The Summary description

#Model Prediction
In this project, I used some the tools such as Text processing, and K-Means Clustering algorithms to get insights from the dataset. And also used some validation techniques to check the accuracy of the model for example Silhouette Score, and Elbow Method.

Conclusion
My model is working well at the n_clusters = 3 which is 0.355.
