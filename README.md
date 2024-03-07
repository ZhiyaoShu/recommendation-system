# Music recommendation-system
The project meticulously explores the domain of music recommendation systems, leveraging a comprehensive approach to understanding and implementing a diverse set of recommendation strategies. The project utilize the application of Singular Value Decomposition (SVD) and the construction of a cosine similarity matrix, two sophisticated techniques pivotal in enhancing the accuracy and relevance of recommendations. These methodologies are employed across six distinct predictive models:
**Popularity-Based Recommendation:** This model leverages the overall popularity of items (songs, in this case) to recommend the most liked or most listened to tracks to users. It's a straightforward approach that assumes what's popular among the masses will likely appeal to individual users as well.
**User Similarity-Based Recommendation:** By analyzing user profiles and their historical interactions with the music catalog, this model identifies users with similar tastes and preferences. Recommendations are then made based on the listening habits of these 'neighbor' users.
**Item Similarity-Based Recommendation:** Similar to the user-based approach, but focusing on the similarities between items. Songs that are similar to those a user has enjoyed in the past are recommended, leveraging item features or interaction patterns to define similarity.
**Model-Based Collaborative Filtering:** Utilizing SVD, this approach models user-item interactions to predict user preferences for items they haven't interacted with. It's a powerful method that can uncover latent factors underlying user preferences and item characteristics.
**Cluster-Based Recommendation System:** This method groups users into clusters based on their preferences and behavior. Recommendations are made within these clusters, assuming that users within the same cluster will likely appreciate similar content.
**Content-Based Recommendation:** Focusing on the attributes of the items themselves, this approach recommends items similar to those a user has liked before, based on content features such as genre, artist, and lyrics.

To evaluate the efficacy of these diverse recommendation strategies, the project employs robust metrics including **F1-score**, **Precision**, and **Recall** .


### **Data Dictionary**

The core data is the Taste Profile Subset released by the Echo Nest as part of the Million Song Dataset. 
song_data <br>
song_id - A unique id given to every song <br>
title - Title of the song <br>
Release - Name of the released album <br>
Artist_name - Name of the artist <br>
year - Year of release <br>
count_data <br>
user _id - A unique id given to the user <br>
play_count - Number of times the song was played <br>

**Data Source:** [Million Song Dataset](http://millionsongdataset.com/)

**Libraries Used:**
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- scipy
- surprise
