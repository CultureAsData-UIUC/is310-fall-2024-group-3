**Song**
This column contains the name of the song that is recorded on the Billboard Top 100. Each column contains information relating to the song. Format: String
**Album**
This is the album in which the song is on. Variances occur in this as some songs are only released as singles, or only in compilation albums after the charting date. Format: String
**Album Release Date**
This is the release of the album that the song is on. Some album release dates are later than the charting date of the song, specifically in the case of songs that are only on compilation albums on Spotify. Format: Date/Time
**Artist Names**	
Contains the names of the artists/bands credited to the song. Format: List of strings
**Artist(s) Genres**
Contains the genre(s) of the artists who are credited to the song. Format: List of strings.
**Hot100 Ranking Year**	
This is the year in which the song charted on the Billboard Hot100 Year End list. Format: Integer
**Hot100 Rank**
This is the position that the song was on the the Billboard Hot100 Year End list. Format: Integer (1-100)
**Song Length(ms)**
Length of the song in milliseconds of how it appears on Spotify. Format: Integer	
**Spotify Link**	
	URL to the song on spotify. Format: String
**Song Image**	
URL to an image of the album on Spotify. Delivered through Spotify’s content delivery domain. Format: String
**Spotify URI**
The URI (Uniform Resource Indicator) that does not contain a https header. Can be entered in the search box in Spotify to directly navigate to the track or album or artist. 
**Acousticness**
A measurement of Spotify’s perceptual algorithm confidence of a tracks acoustic ness. 1 means that there is high confidence that the track has acoustic features (use of acoustic instruments, recording in acoustically rich settings) Format: Float
**Danceability**	
A metric of how danceable a track is based on tempo, rhythm stability, beat strength, and overall regularity. 1 being the most danceable. Format: Float
**Energy**	
A measure of perceived energy or intensity. Factors that contribute to this are described to be dynamic range, perceived loudness, timbre, onset rate, and general entropy. Format: Float
**Instrumentalness**
A confidence metric for whether vocals are detected in the track. Non-word vocalizations are treated as instrumental elements. Values above 0.5 are likely to be instrumental, but values closer to 1 are higher confidence. Format: Float
**Liveness**
A confidence metric for whether or a track was performed live, specifically the presence of an audience in the recording. Values above 0.8 are considered high confidence to be live. Format: Float
**Loudness**
An average of the loudness in a track, which is measured in decibels. Values tend to be from 0db to -60 db. Format: Float
**Speechiness**	
A metric of confidence used to detect the presence of spoken words in the track. 0.66 and above are tracks that are likely all spoken words, 0.33 to 0.66 are the tracks that might contain both spoken word and music, and tracks under 0.33 are likely to be just music. Format: Float
**Tempo**
	The estimated tempo of a track, measured in Beat per Minute. Format: Float
**Valence**
A metric of confidence for the tone/mood of the track. 1 is closer to happiness/euphoria, 0 is closer to sadness/depression. Format: Float

**Key**
A metric detecting the key of the song, with each key being mapped to a range of values between 0-11. -1 means there is no key detected. Format: Integer
**Mode**
In relation to the key, this metric describes whether or not the song is major or minor. Format: Integer
Time Signature
A metric for the time signature of songs, with a range of 3-7. The note value is assumed to be 4. Format: Integer
**Lyrics**
A column containing the lyrics of the song/row. Lyrics were compiled using the Lyrics.OVH api. Some of the songs did not have retrievable lyrics, and thus have the value of, “Lyrics not found”. We left these values in as the entry of the song is valuable information. 

**Data Cleaning**: We erased all entries before the year of 1960, as the entries per year before then do not correlate with the amount of entries that should be there given the top 100 list. 
