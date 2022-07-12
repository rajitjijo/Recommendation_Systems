This Project shall focus on the two basic types of recommendation engines by trying to recommend movies trough both content and collabortive filtering method.


# Recommendation_Systemsm
Recommendation Systems are algorithms that is aimed at suggested relevant items to users based on their likes and previous choices. 

Theyre are generelly two broad types of recommendation systems, the collaborative and the content based. 

Collaborative Models

Collaborative methods for recommender systems are methods that are based solely on the past interactions recorded between users and items in order to produce new recommendations. 
These interactions are stored in the so-called “user-item interactions matrix”.
The class of collaborative filtering algorithms is divided into two sub-categories that are generally called memory based and model based approaches.
Memory based approaches directly works with values of recorded interactions, assuming no model, and are essentially based on nearest neighbours search (for example, find the closest users from a user of interest and suggest the most popular items among these neighbours).
Model based approaches assume an underlying “generative” model that explains the user-item interactions and try to discover it in order to make new predictions. 

Content Based Models

Unlike collaborative methods that only rely on the user-item interactions, content based approaches use additional information about users and/or items. If we consider the example of a movies recommender system, this additional information can be, for example, the age, the sex, the job or any other personal information for users as well as the category, the main actors, the duration or other characteristics for the movies (items).
Then, the idea of content based methods is to try to build a model, based on the available “features”, that explain the observed user-item interactions. Still considering users and movies, we will try, for example, to model the fact that young women tend to rate better some movies, that young men tend to rate better some other movies and so on.
If we manage to get such model, then, making new predictions for a user is pretty easy: we just need to look at the profile (age, sex, …) of this user and, based on this information, to determine relevant movies to suggest.
