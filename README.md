# Unsupervised-Machine-Learning
Netflix Movies And TV Shows Clustering


Intoduction

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.


In this project, we focussed on

Exploratory Data Analysis

Understanding what type content is available in different countries

Is Netflix has increasingly focusing on TV rather than movies in recent years.

Clustering similar content by matching text-based features



Attribute Information

show_id : Unique ID for every Movie / TV Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / TV Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Release year of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genre

description: The Summary description



Steps

Initially, in the 1st step imported the data set to carry out the analysis over the data set to comprehend and handle the missing values and duplicate values. 
 
Performed the Exploratory data analysis and tried to get the understanding of the data and how the content is distributed in the dataset, its type and details such as which countries are watching more and which type of content is in demand etc. has been analyzed in this step with the help of visualization graph by getting insights from analysis. 

Data preprocessing – in this we remove the punctuation and stop words also used stemming to reduce words to their basic form or stem, which may or may not be a legitimate word in the language.

We used the k-means clustering algorithm and then checked the model performance using Silhouette’s coefficient and elbow method to find the number of clusters.



Conclusion:

Applied different clustering models Kmeans, hierarchical, Agglomerative clustering on data we got the best cluster arrangments

By applying the silhouette score method for n range clusters on dataset we got best score which is 0.348 for 3 clusters it means content explained well on their own clusters, by using elbow method after k = 3 curve gets linear it means k = 3 will be the best cluster

we get the optimal number of cluster is equal to 3.
