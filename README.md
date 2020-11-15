
# RiSK: Analysis of the Changes in Popular Music in the World

**Project Summary**

Our study answers the research question: does our data provide sufficient evidence that the proportion of songs in non-English languages has increased from the time period of 1956-1989 to the time period of 1990 to present and that the standard deviation in `Acousticness` has increased over time? The goal of our report is to observe how popular music has shifted to be more diverse in the characteristics of non-English genres or `Acousticness` over time. We used linear regression to analyze the standard deviation of acousticness per year, and a hypothesis test to determine if the proportion of foreign language songs has increased overtime, showing the increased variability of popular music overtime. 


**Variables in Dataset**

`Title`: title of the song

`Artist`: the musician/group who performed the song

*`Top genre`: genre of the track*

*`year`: year it was released*

`Beats per minute(bpm)`: tempo of the song

`Energy`: how energetic the song is

`Danceability`: how easy the song is to dance to

`Loudness(dB)`: how loud the song is

`Liveness`: the likeliness of the song being a live recording

`Valence`: how positive a song is

`Length(duration)`: the length of a track

*`Acousticness`: how acoustic a song is*

`Speechiness`: how much spoken word is in the song

`Popularity`: how popular a song is

(Italicized variables indicate ones used in our study)

**Created Variables**

`decade`: categorical variable indicating the decade when the song was created using the categorical name of "50s", "60s", and so on

`period`: categorical variable in which "Oldies" represents when Year is before 1990 and "Present" for when Year is after 1989

`foreign_lang`: categorical variable in which "TRUE" stands for any song whose `Top Genre` name indicates that the song is spoken in a non-English language, "FALSE" otherwise

`pop`: categorical variable in which "TRUE" stands for any song whose `Top Genre` name has "pop" in it, "FALSE" otherwise

`sd`: standard deviation of Acousticness per year 

`year`: numerical variable representing the years since the first Year in our data set (1956)