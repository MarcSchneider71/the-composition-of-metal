# The Composition of Metal
Exploratory data analysis on popular genres in comparison to metal using Spotify API and lyrics from Genius.

## Sources of Data
I used Spotify's generated playlists for 4 different genres (Pop, Hip-Hop, Latin and Metal). In general these playlists contained the top 100 tracks for these genres although it so happened that Latin only contained 50. I pulled features for these tracks from Spotify's API which can be recreated from the jupyter notebook Metal & Top Hits EDA. You will need to refresh the access tokens to get the updated information or you can use the provided data saved in the dataframe csv file. Using those tracks I then scraped their lyrical content from Genius using a rudimentary Selenium bot which searched for the given artist name and track name and went to the first search result (note that this resulted in landing on articles by accident). 

## Analysis
A comparative 5 number summary plot was made for some key features to compare the genres quantitatively although the features often sought to describe a qualitative feature about the music. To get a feeling for the genres' topics at a glance I then created a word cloud from the scraped lyrical content which was not censored or filtered in any way. This word cloud was then mapped onto an image mask that I found online. 
