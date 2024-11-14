## Selected Methods


### Correlation Analysis and Time Series Modeling (And the Beat Goes On"):
- Application: Use correlation analysis to identify relationships between song characteristics (e.g., tempo, key signature).
- Additional Insights: Time series modeling could help track how these relationships evolve over time to better understand how billboard has changed, possibly in relation to it's metrics and shifting music mediums.

### Speculative Data and Gap Analysis with Prophet (Missing Data, Speculative Reading):
- Application: Use the Prophet model to account for missing or incomplete data, especially if you have periods in Billboard data with gaps or anomalies. This can help in creating speculative insights and identifying potential biases or missing factors within the data.
- Additional Insights: Might be useful in understanding what the gaps in spotify/billboard data set might be, would require a method to integrate outside context with computing.

### K-Means and Agglomerative Clustering (What Makes a Song Trend?"):
- Application: K-means clustering can help categorize Billboard data into different musical clusters based on attributes like tempo, energy, and valence. Use agglomerative clustering to validate the number of clusters for a reliable grouping of song features.
- Additional Insights: Cluster analysis will reveal which characteristics dominate in popular music and how these clusters shift over time, similar uses as correlation analysis. Would be used in conjunction with a study of the changes that billboard has made to it's metric system.
### Song Feature Extraction
- Application: We would use a python library or possibly machine learning to attempt to reverse engineer the perceptual features included in the spotify dataset.
- Additional Insights: Spotifies algorithm for determining these features is proprietary, diong this would be quite rigirous but seemingly acheiveable given we find the right library.

