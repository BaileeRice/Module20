# Module20
## Segment #3
### README.md should include:
Cohesive, structured outline of the project (this may include images, but they should be easy to follow and digest)

For this project, we were interested in seeing just how efficient a machine learning model will be at accurately predicting the genre of a song. We obtained dataset from Kaggle as it was one of the most popular ones out there, and from this dataset we decided to focus on four specific genres; Rock, R&B, Country, and Rap.
(https://www.kaggle.com/datasets/thedevastator/popularity-of-spotify-top-tracks-by-genre?select=rap_playlist_tracks.csv).

With access to the many files containing different data about genre, we decided to only use the playlist track data and focused on 11 specific attrubutes as shown on the image below. These attributes were chosen because we felt as though they would increase the accuracy of the predictions made by the machine.  
![Screenshot (30)](https://user-images.githubusercontent.com/108035567/202317031-8bd8353f-dd4a-4a2d-834c-8db15c10eaa2.png)

A master data frame combining all data from all three genres was created and from this table we 

Although unsupervised machine learning was a successful at showing patterns within the data as it relates the genre, it was not the best at accurately predicting genre while taking into consideration the 11 attributes in the table above. 
A supervised version of the machine learning model was created, and upon testing, we found that it had a balanced accuracy score of 72.6%. We also found that speechiness, danceability, and acousticness were the top three biggest contributors of accurate genre prediction as shown in the image below.
mj![image](https://user-images.githubusercontent.com/108035567/202345398-939cf29c-c16e-4986-9940-9c183b9472ce.png)

