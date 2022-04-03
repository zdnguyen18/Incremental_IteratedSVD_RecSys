# Updated_IteratedSVD_RecSys
Using updated Iterated SVD to improve the Recommendation System for Netflix (Movielens datasets)
**OBJECTIVE:**
In recent years, the need for more accurate recommender systems to improve user interaction and provide more personalized services on eCommerce platforms such as Amazon and Netflix has been increasing globally. The motivation results from a desire to help users find an appropriate product that fits their tastes and meets a variety of special needs, enhancing users’ satisfaction and loyalty.  However, with the overload of vast amounts of customer data, recommender systems face challenges in processing data robustly and accurately. This proposal focuses on designing a movie recommendation system that works for offline and online processes, meaning performs well when new data is added to the original dataset.  The base algorithm in my paper is Singular Value Decompositions (SVD), an applied matrix factorization method of the item-based collaborative filtering model. To solve scalability matters and reduce the expensive matrix factorization steps, the updated Iterative SVD is expected to improve in prediction accuracy and run time. 

**DATA**
In this project, I used the “MovieLens” database, developed by the GroupLens research lab at the University of Minnesota.
The initial data set consisted of ~100,000 user ratings; then was reduced to ~47,000 once both users and movies with low number of ratings were removed to combat high matrix sparsity of around 99%. My final dataset included information on userId, movieId, rating, title, genres and year.

**MAIN PART**
1. *Exploratory Data Analysis and Post-Modeling:* emphasize the spread of movie ratings by looking at distributions and visualize the popular movies in each genre. Moreover, the EDA post-modeling step helps me figure out the differences between initial ratings and ratings after using model. From that, we can conclude about how accurate the model performed.
2. *Recommender Modeling:* Starting with a baseline SVD model without tuning any hyperparameters or making changes in algorithm, I will explore how updated Iterated SVD perform in term of accuracy and speed.
3. *Software demonstration video*
