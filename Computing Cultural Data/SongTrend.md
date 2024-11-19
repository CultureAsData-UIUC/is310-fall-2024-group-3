# What Makes a Song Trend?
[(https://articlearchives.co/index.php/JMDC/article/view/4610)]
## Summary:
In this study, California State Polytechnic University researchers looked at what metadata correlated with a song's position on Spotify’s "Top Song" charts using Spotify API data. Similar to our project, they looked at "Top 100" 2017 and 2018 songs and looked at attributes like danceability, energy, loudness, and tempo.

They found that high danceability, valence, and low speechiness dominated the top 100. In Cluster 1, songs with high danceability, positivity (valence), and low speechiness were most prevalent in popular clusters, aligning with Pop and Dance genres. Listeners enjoyed high-energy, positive music with minimal spoken word content.

While Cluster 1 heavily dominated the top 100, smaller clusters, like Cluster 3 in 2018, with unique attributes (high energy and tempo, low danceability) aligning with Alternative music, showed that there was room for more niche genres. They also noticed a trend of increased tempo in 2018, possibly due to faster-paced Hip-Hop. They suggested that this could be attributed to evolving listener tastes.

The study concludes that song attributes are essential to chart success, with trends shifting over time. Understanding these dynamics can guide production, marketing, and playlisting. Future research could explore artist identity and genre’s role in hit-making.

[(https://ibb.co/sKB74LP)]

## Computational Methods:
The authors have used the application of k-means clustering and agglomerative clustering while analyzing data on Spotify's "Top 100" songs for the years 2017-2018. K-means clustering: This is one version of an unsupervised machine learning algorithm that segments a set of data points in a multidimensional space into some specified number k of nonoverlapping clusters of data points with similar characteristics. Its objective is to minimize intra-cluster distances and maximize inter-cluster distances. The k-means clustering was realized by the authors using the Python programming language. This picture better visualizes this. By getting these clusters, we can then analyze why the data is similar.

[(https://ibb.co/CVJgfWR)]

Agglomerative clustering is a way to group data points by starting with each cluster and then gradually merging the closest groups together. This process continues step-by-step until all the points end up in one big group. The result is a diagram called a dendrogram that looks like a branching tree, showing how groups combine at each step. In the study, agglomerative clustering was used as a check. After they figured out the best number of groups to use k-means clustering, they applied agglomerative clustering to see if it agreed with their choice of k. This helped confirm that their initial grouping was accurate.

[(https://ibb.co/wrpBJsG)]

## Project Application:
I think we can definitely use either one or two of these methods for our project. K-means is fast and handles large datasets well, which will work well for our billboard data. K-means also reveals general patterns in song characteristics within the clusters it makes.

Agglomerative clustering seems to go hand in hand here to confirm the k-means results, validating the number of clusters.

