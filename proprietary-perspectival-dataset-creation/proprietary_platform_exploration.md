*   Step 1
    

1.  We are selecting Spotify as a streaming service
    

*   Step 2. Review Terms of Service & Access Limitations
    

1.  Locate and investigate the platform’s terms of service. Does it mention anything regarding data access? How clear is it on whether users can download their personal data?
    

*   Spotify does allow users to download their personal data
    
*   Users can go into their privacy setting page, and request a download of their personal data. Spotify then sends a link through your email to the download of the personal data once the request has been processed and approved
    
*   Some data that is not as accessible is data that is shared with third parties
    

3.  Research if the platform offers any bulk or academic access options and whether this requires a fee or application to utilize it.
    

*   Spotify gives limited access for bulk or academic access, however it has a separate public api which is accessible to all. This is composed of limited metadata. 
    
*   To access more specific data or data for bulk usage the user will have to submit a special request which is not guaranteed to be granted. 
    

5.  Identify how, if at all, researchers are accessing data from this platform. Are there any tools or APIs that facilitate this process?
    

*   The software developer guidelines are very strict on how the data can be used. 
    
*   It is prohibited for anyone to use the data for machine learning purposes
    
*   Spotify typically only allows for the use of their data for personal use
    
*   The data that is allowed to be used is all in the Spotify web API. The Web api contains the basic metadata of songs.
    
*   Researchers can just use the public data available but some need more specific access which is why a formal request would be required to access that data. 
    

7.  Using resources like the Internet Archive’s Wayback Machine, explore how these terms of service have changed since the platform first launched. Have restrictions increased or decreased over time?
    

*   When spotify was first launched there were fewer restrictions and policies on personal data, but there was also less functionality in accessing personal data.
    
*   A change that came in the future was that personal data became more accessible because users could download their personal data. 
    
*   The early API policies were also a lot less restrictive than now. Third party developers were able to integrate spotify data into their apps with more ease
    
*   Now restrictions are very strict and defined so use of the spotify data for other purposes than personal, is a lot harder. 
    

  

*   Step 3. Document Findings
    

When accessing data from Spotify for research, there are several barriers. First, there is API Access Limitations. As the API has rate limits, researchers in different areas will/can access different music data based on where they are. If the music research is regarding world music, this can be a problem as the music data collected just in one area can be incomprehensive and biased. We should also not forget that Spotify can change its API. Over a certain, researchers might not be able access the same music data or features when Spotify changes its offerings. When the API changes, researchers may face issues in reproudcing or referencing from the past research to continue the studies. Moreover, not all data is available through Spotify. Some information such as geographic and demographic can be hard to find as listening history needs Spotify users’ consent in sharing their listening or searching history. This will make the analysis on the change of music trends somehow challenging. Talking about consent, this involves the considerations of data privacy and ethics. Privacy and ethics concerns can limit what music data can be accessed and how it can be analyzed. The users data is linked to personal preferences or emotions from their listening habits so researchers have to follow the ethical guidlines while doing the music related research. Lastly, in Spotify’s Terms of Service, the business has put various safeguards in place to guard against unauthorized access and unnecessary retention of personal data in the system. Therefore, the music data can not be used or redistributed without explicit permission, which can make collaboration on research challenging as it is possible that researchers will violate legal obligations while working on music dataset. 

  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfsTReQkWFBwb_8ZMrJDhtDN9nL_QhkNSaI2yZnFRYMcq0mdCaTYmlo7duV-D26tj2rhpiyQwQEH93PGb36J54c3gulFWZmhr47yioXxSDeE6y8h-C_WtPvG0ITQYkA9BUebfqT4yywon1TMIuD?key=P4_i5Bu3oSPiNGPQh-Rn2Q)

Part 2

  

Step 1 And 2: Platform Data Collection & Considerations

  

To first collect our data sample, we realized we would need to cut some of the fat off. Our dataset has about 35 columns, many of which were not related to our project and analysis. Not only that but it made it rather cumbersome to look through. We decided to taper the set to 14 columns for these reasons. —

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdQMYxBDlQh28_o2ers4m4myMhKfPp8SQ5raS1ajbAH9skPWkSdln1MgvZP9lMkOW7Ny53eXOyvE5dvAa2PIuvxh-U5FOm7xZf1JxWNViozYPreV416Kp5hoiG8fRj9J16JmcTXG3aA8g5NDzzsxg?key=P4_i5Bu3oSPiNGPQh-Rn2Q)  
We decided to add a “In my playlist” column signifying whether any one in the group had one of the songs in their playlist. We chose this topic because it relates to our project question of analyzing music trends and we are taking part in small why by collecting information on what people are listening to in 2024. —-

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfgMu6yJK-nqPk_NJsBv0UBSIwhSfwjtV7_S2dv9HYV4I3hW8PFwazf4jhiFUK6N9b2oxD_9klqdmMqTUWXYWxdBeeDCKGpVmhFZotYI8A457UuwwNRTTV8sNrZtu8uETQOMfRWT78zND59YryJ?key=P4_i5Bu3oSPiNGPQh-Rn2Q)  
  
.Here is a sample from our dataset.

—-

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfL1NA_MXd3-GAj1NcdlvuBbbe3np9IRv1ES6DnlQjEsCL_aRjhEeFSiFAgq3ZD4mFnWR81U0bvvSZZZdR-thjlJkuNuf0b-cKwdDZ90v2buTJ_oYufh9zs9FlqnAUGY74B4sq0hJwDW9a5u2l4HQ?key=P4_i5Bu3oSPiNGPQh-Rn2Q)

  

Part 3: Reflect & DocumentPermalink

Documenting The Data

  

Our dataset consists of 10 rows of data, with 14 columns. Each row consists of a song selected from the larger dataset, with basic information of the song, including song name, artist name, song release date, and song duration and album title. Then there are 7 columns with spotify generated data that give insight into the perceptual experience of the song. These include danceability, which uses tempo, rhythm stability, beat strength, and overall regularity to calculate how danceable a track might be. Another perceptual feature is energy, which uses spotify metrics for dynamic range, perceived loudness, timbre, onset rate, and general entropy to calculate the intensity of a track. The final perceptual feature is valence, which is a metric for how happy or sad a song might be perceived with values closer to 1 being happier and 0 being sadder. The completeness of the data is decent, with there being at least one song being represented from each decade since the 1960’s. There is a good amount of relevant data in relation to the factual information of the song. There needs to be more research done on the collection of Spotify perceptual features. The main issue is that this is a 10 song sample of a very large Spotify dataset. 

  

Reflecting on The Data

  

We determined the In My Playlist column because we felt that we wanted a metric for which we could understand the relevance these songs had to the actual way that people were listening to music away from the metrics of this data set. There were discrepancies in how we interpreted the data, somewhere unsure if this column was intended to represent people outside our group or just relevant to the people inside of our group. Since there was a large amount of Spotify data on the larger dataset, we felt it would be reasonable to do a random sampling of the data in order to slim down the data significantly. There were not any difficulties in doing this that we encountered in doing this. The main platform dynamics that are depicted in this dataset are the ways in which Spotify quantifies perceptual experiences and uses these metrics to then recommend and push music. These metrics may not be particularly meaningful on their own, but in the ecosystem of Spotify with its user metrics, these features allow for Spotify to behave closer in accordance to what it knows about its users. Although Spotify tries to quantify perceived danceability and happiness, oftentimes the experiences of these things can be nuanced and varied in ways that are not numerically quantifiable. 

  

Licensing The Data

For our project, we have decided to license our dataset under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). This choice allows others to share and adapt our dataset, provided they adhere to specific guidelines. Users must credit our group as the original creators whenever they utilize the dataset and include a link to the license, which can be found here: Creative Commons Attribution-NonCommercial 4.0 International License. Additionally, if any modifications are made to the dataset, it is essential to clearly indicate what changes have been made.

It is important to note that this dataset is strictly licensed for non-commercial purposes. Any use that involves commercial gain, such as selling the data or incorporating it into a monetized product, is prohibited. Also, users should maintain the integrity of the data by avoiding alterations that misrepresent the original findings or methods. When sharing adapted versions, it is important to provide context so that the original intent is preserved.

We also emphasize the importance of ethical considerations when using this dataset. Users should respect the privacy of individuals represented within the data and be mindful of any sensitivities associated with the information. The potential implications of using this data, particularly regarding vulnerable populations, should always be considered.

For a complete understanding of the terms associated with our dataset, please refer to the “LICENSE” file included in our repository. This document outlines the rights and responsibilities related to the use of our dataset.
