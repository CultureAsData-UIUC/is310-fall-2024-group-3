**Dataset identification and comparison:** One or more members should focus on finding relevant datasets (historic and contemporary) or data points from previously identified datasets.

[https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now](https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now)

[https://www.kaggle.com/datasets/tushar5harma/billboard-hot-100-songs-spotify-data-1946-2022?select=Billboard\_Hot100\_Songs\_Spotify\_1946-2022.csv](https://www.kaggle.com/datasets/tushar5harma/billboard-hot-100-songs-spotify-data-1946-2022?select=Billboard_Hot100_Songs_Spotify_1946-2022.csv)

### **Questions for Historic vs. Contemporary Datasets Reflection**

**1\. How do these datasets differ in how they represent cultural objects or practices?**

*   Compare how the digital object itself and the dataset convey the same cultural artifact. What details are maintained, and what are simplified or lost?
    
    *   Both sets of data follow similar guidelines as to the objects represented and the information that is included within each object. Both are datasets that are based on Spotify data, with the goal of being stratified by year. Within each entry of both datasets, song names, song links, artist and album names, spotify genres, and song duration. There are also Spotify metrics that give information around the auditory experience of a song. These metrics tend to be a bit more abstract, descriptors like danceability, liveness, loudness and speechiness. 
        
    *   The main difference between these datasets is the inclusion of a record label column in the contemporary dataset. 
        
    *   The cultural artificat being conveyed in this data set are the songs that are being released in their respective years, as well as the information about the songs. The distributions of genres and their changes.The way that genres form and change are generally fluid and organic. Oftentimes genres are labels created by listeners and consumers of said art, or retrospective labels. The genre assignments given by Spotify can give us an idea of how things changed over time, but won’t be able to communicate the nuances of the evolution of music in relation to how artistic movements, people and culture have interacted. Furthermore, these digital representations are only the names and extractable information that Spotify has deemed worthy or representing. We gain no understanding of the actual art/cultural artifact being represented, just a symbol for it’s qualities. 
        

**2\. What kind of metadata or context accompanies the data?**

*   Evaluate the transparency of the dataset about its origins, creation, and curation process. Is there sufficient context provided to fully understand the cultural object?
    
*   The dataset for the top 10000 from 1960 to now was curated based on ranking from ARIA which is the Australian Recording Industry Association and Billboard Chart. There is not a lot of metadata provided, the only thing that is provided is the Provenance which is Spotify. The sources that are used in this dataset do give sufficient context to understand the cultural object because billboard is the most reliable music ranking chart that anyone thinks of when it comes to looking for top songs. By adding the ARIA it also adds some diversity to the dataset which takes away some of the power that Billboard would hold over the dataset. 
    
*   The second dataset of top 100 billboard songs and it was made by scraping data from wikipedia about the billboard top 100. There is not much metadata provided about this dataset except for sources of wikipedia and spotify. 
    

 **Does the dataset reflect any power structures or biases?**

*   Discuss how the dataset’s structure, curation, or presentation reflects specific power structures. Consider who controls the dataset, what narratives it promotes, and whose perspectives are centered or marginalized.
    

Yes, the dataset clearly reflects power structures and biases, particularly in the dominance of certain artists, genres, and labels. For example, Taylor Swift, P!nk, Elvis Presley, and Ed Sheeran are heavily represented, with Taylor Swift appearing 48 times. This suggests a bias toward globally popular artists with significant influence in the music industry. These artists are often backed by major record labels, which have the power to promote their music more widely, resulting in their overrepresentation in the dataset. Similarly, certain genres, such as pop and dance pop, dominate the "Artist Genres" and "Album Genres" columns, appearing hundreds of times. This suggests a focus on mainstream genres that are more commercially successful, potentially sidelining niche or regional genres.

In terms of labels, Universal Music Group, Columbia, and RCA Records are the top three represented, which reflects the concentration of power in a few major corporations in the music industry. These large labels have far more resources to promote their artists and push their music to the top of the charts, reinforcing their dominance in datasets like this one. Smaller, independent labels, on the other hand, are sparsely represented, indicating a structural bias toward artists supported by industry giants. The dominance of major labels and mainstream genres reinforces the narrative of commercial success being equated with cultural significance, potentially marginalizing other musical voices and genres.

**4\. Are there any notable gaps in the data?**

*   Analyze what might be missing from the dataset that was part of the digital object. Why do you think this data is missing? Is it due to technical limitations, a lack of value, or active suppression?
    

There are notable gaps in the data. One significant gap is in the Artist Genres column, where 550 entries are missing. This is a large proportion of the dataset, and it indicates that genre information for many tracks or artists is either unavailable or was not included in the dataset. This absence could be due to technical limitations or a lack of emphasis on genre information in certain cases. Additionally, the Track Preview URL is missing for 2,897 entries, which means that users cannot easily access a preview of many songs. This could be due to licensing restrictions or missing data during the curation process.

There are also minor gaps in other columns such as Track Name, Artist Name(s), Album URI, and Album Release Date, but these are relatively few in number and are unlikely to significantly impact the overall analysis. However, these gaps do suggest that some records in the dataset are incomplete, which could affect the accuracy of any genre- or artist-specific analyses.

Finally, the Year Distribution shows a skew toward more recent years, particularly 2019, 2020, and 2021, with fewer entries for earlier years like the 1950s and 1960s. This indicates that there may be an underrepresentation of historic data, which could skew analyses that attempt to make comparisons over time. This gap could be due to the availability of data, as older records might not be as thoroughly digitized or available on platforms like Spotify.

By the end of this part, your group should have documented the differences and similarities between historic and contemporary datasets, focusing on how they represent cultural objects or practices, what is missing, and the power dynamics embedded in them. **You are encouraged to make connections to our class readings so far, whether through direct citations or general connections.**

**AI analysis: One or more members should be responsible for generating AI outputs for at least one digital object and dataset pair and analyzing the results.**

Our group decided to use **ChatGPT** as our main tool in AI analysis. In ChatGPT, it first gives us a dataset summary for both the historic and contemporary dataset. In our **historical dataset**, the digital objects are the songs and their associated metadata, all represented in digital format. ChatGPT analyzed various aspects such as the distribution of songs by year, top artists, top genres, audio features, and Hot100 rank distribution. During the analysis, an error related to the "Genres" column occurred while processing the distribution of songs by year and the most represented artists and genres. ChatGPT identified the issue, corrected the code by using the correct column name, "Artist(s) Genres," and proceeded to generate accurate results. Finally, it provided insights into the most popular artists and genres in the Billboard Hot 100 dataset over the years.

For our **contemporary dataset**, ChatGPT first gives us the general information of year, popularity, and duration of each song. When analyzing cultural objects, ChatGPT gives an idea of the diversity of genres in the dataset, ranging from rock and pop to electronic, hip hop, and metal. In addition, ChatGPT provides detailed information about various musical genres associated with artists on Spotify including key genre features and patterns and insights without the codes. Many entries also include niche or hybrid sub-genres that highlight the complexity of the music landscape. For instance, it demonstrates that Acid House, Ambient House, Big Beat, Hip House are sub-genres of electronic dance music, popular in the late 1980s and early 1990s. Dance Pop, Miami Hip Hop, Pop are the ones that represent mainstream music styles, with "Dance Pop" being a popular music genre that combines dance rhythms with pop music, while "Miami Hip Hop" is a subgenre of hip hop originating from Miami. 

In conclusion, AI-generated datasets typically provide both summaries and detailed descriptions of our cultural and digital objects. While ChatGPT may occasionally encounter errors, it continuously works to resolve them, striving to retrieve the requested information and demonstrating the steps taken to correct any issues.

**Questions for AI Reflection**

**1\. How does the AI describe the cultural object versus the dataset?**

**Are there differences in how the AI represents the cultural artifact when describing it as a digital object compared to the dataset? What nuances or context is lost in the dataset?**

When describing the cultural object,  it provides a narrative. It delves into the diversity and complexity of the genres, highlighting their historical origins, and unique characteristics. For example, it explains how genres like Acid House, Ambient House, Big Beat, and Hip House are sub-genres of electronic dance music popular in the late 1980s and early 1990s.

In contrast, when the AI describes the dataset, it uses a technical perspective. There’s a focus on the structure, variables,  and ranges of the dataset. It summarizes numerical attributes such as years covered, popularity scores, and song durations. It also provides code snippets/references to the methods used to obtain these summaries.

**2\. What does the AI’s output reveal about the dataset’s embedded power structures?**

**Does the AI’s language reflect any inherent biases or reinforce specific power dynamics? How does the AI’s interpretation of the dataset compare to the object’s original context?**

      The AI's output reveals that the dataset contains embedded power structures that prioritize mainstream, Western music genres, and accentuate popularity and commercial success. There are inherent biases in focusing on certain genres while potentially neglecting others, reinforcing existing power dynamics in the music industry.       

       This interpretation differs from the cultural object's original context, as it lacks the understanding of the genres' cultural, historical, and social significance. The AI's dataset-centric approach leads to a loss of context that doesn’t fully capture the diversity of the musical landscape.

**3\. What is potentially missing in the AI-generated descriptions?**

**Consider whether the AI recognizes or highlights any missing information. Does it attempt to fill in these gaps, and if so, how accurate or reflective are these attempts of the original cultural object or practice?**

The AI-generated descriptions are often missing critical elements needed for a full understanding of the music genres. The AI typically doesn't recognize these omissions and ties to fill the gaps of understanding by relying on generalizations or existing knowledge.

**4\. Does the AI challenge or reinforce existing narratives?**

**Reflect on whether the AI critiques or reinforces dominant narratives about the cultural object or practice. Does it repeat common assumptions, or does it present new insights that challenge the status quo?**

In this context, AI reinforces existing narratives rather than challenging them. It highlights mainstream, Western music genres, and focuses on popularity metrics. This reinforcement is largely due to the data-driven nature of AI and the lack of safeguards within its programming to question or critique the information it processes.