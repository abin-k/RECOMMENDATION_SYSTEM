# MUSIC RECOMMENDATION SYSTEM

Music recommendation systems have become increasingly important in recent years, particularly with the rise of 
music streaming services. These systems are designed to suggest songs or playlists to users based on their 
listening history, preferences, and other factors

![HELLO-FUTURE-1198x500-ALGO](https://user-images.githubusercontent.com/116078614/233829760-994e71cc-6309-428a-aaa7-b5759c4a2e9d.jpg)

why Music recommendation systems are relevant?

Personalization: Song recommendation systems can provide personalized music recommendations to users based on their past listening behavior, which makes the listening experience more engaging and enjoyable for the user.

Discoverability: Song recommendation systems can help users discover new music they may not have found on their own, exposing them to a wider variety of genres and artists.

Engagement: Song recommendation systems can keep users engaged with a platform, driving up user engagement and retention rates.

Revenue: Song recommendation systems can lead to increased revenue for music streaming platforms and artists, as they can promote songs and artists that users may not have discovered on their own.

User satisfaction: Song recommendation systems can improve user satisfaction by reducing the amount of time users spend searching for music, and instead providing them with a personalized and enjoyable listening experience.


# 1.Recommendation system based on cosine similarity
Developed a content based Music recommendation systems based on cosine similarity and TF-IDF vectorizer. 

Cosine similarity is a mathematical technique that measures the similarity between two vectors. In the context of music recommendation, cosine similarity can be used to compare a user's listening history with the music in a database and generate recommendations based on the similarity between the user's listening history and the music in the database.

TF-IDF vectorizer is used to convert song into a vector representation that can be used to compute similarity scores between songs.
TF-IDF vectorizer is a powerful tool for music recommendation as it allows for a quantitative analysis of the songs and can help identify songs with similar themes and subject matter.

![Screenshot (1)](https://user-images.githubusercontent.com/116078614/236270153-818caa83-71c8-440f-9ee4-4167ac7c299e.png)

The features which are extracted for the model training are SONG NAME, ARTIST NAME & GENERE. The model will recomment new songs based on these features of previous song



# 2.Recommendation system based on k-means clustering 
Developed a Music recommendation systems based on k-means clustering, an unsupervised clustring methode. 
 Here all the other features of song such as Tempo, Energy,Chord, Acousticness, Loudness, Streams etc are considered in training the model.
 The predicted song will have these similar features as the referral song

![Screenshot (38)](https://user-images.githubusercontent.com/116078614/236272761-c84bbaab-5fc5-4c53-896c-779d37de9e38.png)

