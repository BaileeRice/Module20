# Spotify Analysis

For this project, we were interested in seeing just how efficient a machine learning model will be at accurately predicting the genre of a song. We obtained dataset from Kaggle as it was one of the most popular ones out there, and from this dataset we decided to focus on four specific genres; Rock, R&B, Country, and Rap. All genre were solely chosen based on the fact that they contained the most data collected by spotify as shown in the graph below.
(https://www.kaggle.com/datasets/thedevastator/popularity-of-spotify-top-tracks-by-genre?select=rap_playlist_tracks.csv).


![Screenshot (35)](https://user-images.githubusercontent.com/108035567/202359198-47dad07c-8e77-4593-bb97-fb51b2b11e0f.png)



With access to the many files containing different data about genre, we decided to only use the playlist track data and focused on 11 specific attrubutes as shown on the image below. These attributes were chosen because we felt as though they would increase the accuracy of the predictions made by the machine. 

![Screenshot (30)](https://user-images.githubusercontent.com/108035567/202317031-8bd8353f-dd4a-4a2d-834c-8db15c10eaa2.png)


Using the K-means clustering method we created an unsupervised machine learning model. The image below depicts a snipet of the code we used for the mlm. The number of clusters represents the four genres we'll focus on for the project.

![Screenshot (33)](https://user-images.githubusercontent.com/108035567/202354197-a276d178-1cfb-41e0-a73a-23f4cb06991d.png)


Although unsupervised machine learning was a successful at showing patterns within the data as it relates the genre, it was not the best at accurately predicting genre while taking into consideration the 11 attributes in the table above. The image below shows one of the patterns found using this model. The tableau link below will allow you to manipulate the attributes and see the patterns.

![2022-11-16 (2)](https://user-images.githubusercontent.com/108035567/202358443-755b6166-9f1d-420a-9df0-16e3231e4444.png)


A supervised version of the machine learning model was created, and upon testing, we found that it had a balanced accuracy score of 72.6%. We also found that speechiness, danceability, and acousticness were the top three biggest contributors of accurate genre prediction as shown in the image below.

mj![image](https://user-images.githubusercontent.com/108035567/202345398-939cf29c-c16e-4986-9940-9c183b9472ce.png)

Slides:https://docs.google.com/presentation/d/1y_DgnlQ9wYASojwS9idZCyP-hs8Qp631jknh44w6OYo/edit?usp=sharing

Tableau:https://public.tableau.com/app/profile/melanie.taylor6095/viz/Spotifyset/Story1

