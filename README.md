# recommendation-system
In an era where information overload is commonplace, recommendation systems serve as a crucial interface to curate personalized user experiences, thus helping platforms retain and grow their user base amidst competition. The primary goal of this project is to learn and develop six distinct types of recommendation systems. By employing different methodologies, this project aims to clarify each approach in providing accurate and meaningful recommendations.

### **Importing Libraries and the Dataset**
**Data Dictionary**

The core data is the Taste Profile Subset released by the Echo Nest as part of the Million Song Dataset. There are two files in this dataset. The first file contains the details about the song id, titles, release, artist name, and the year of release. The second file contains the user id, song id, and the play count of users.

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

### Popularity-based recommendation systems
Popularity-based recommendation systems are the most basic recommendation systems. These systems are non-personalized and are based on the frequency of the items. The items that are more popular are recommended more often.

### User similarity-based collaborative filtering
User similarity-based collaborative filtering is a method used to make automatic predictions about the interests of a user by collecting preferences from many users. The underlying assumption is that if a user A has the same opinion as a user B on an issue, A is more likely to have B's opinion on a different issue than that of a randomly chosen user.

### Item item similarity-based collaborative filtering recommendation systems
Item-item collaborative filtering is a type of collaborative filtering for recommender systems based on the similarity between items calculated using people's ratings of those items.

### Model based collaborative filtering - matrix factorization
Model-based Collaborative Filtering is a **personalized recommendation system**, the recommendations are based on the past behavior of the user and it is not dependent on any additional information. We use **latent features** to find recommendations for each user.

### Cluster based recommendation system
Cluster-based recommendation is based on the idea of grouping similar items or users together. The idea is to recommend items to a user that are liked by other users in the same cluster as the user.

### Content based recommendation
Content-based filtering methods are based on a description of the item and a profile of the user’s preferences. These methods recommend items that are similar to those that a user liked in the past. The similarity of items is determined by the similarity in their properties.