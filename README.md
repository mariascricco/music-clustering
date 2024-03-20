# music-clustering

## The following code in Python utilizes the Spotify TidyTuesday dataset, which is linked: here [https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-21/readme.md]

# The goal is to investigate which music genres are closest to the Pop genre, and to one another based on Spotify data. 



## The dataset was cleaned from this original github link, ommitting all columns except:
## - genre
## - key
## - mode
## - tempo
## - duration
## - popularity

## Next, the data was shortened to contain the top 10 songs per genre based on popularity, and standardized in order to make each value on a single scale. (value - mean/std)
## A Principal Component Analysis and Singular Value Decomposition was then run on this dataset.

## A second dataset was created based on standardized data averaging each of these 10 songs.
## A second Principal Component Analysis and Singular Value Decomposition was then run on this dataset.

