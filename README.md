PROBLEM STATEMENT
Create a Recommendation Engine from the ground-up, where every single
user, based on the area of interest and ratings, would be recommended a
list of movies that are best suited for them.

OBJECTIVE
The project objective of the Netflix recommendation project using Singular
Value Decomposition (SVD) is to create a recommendation system that
can predict how a user would rate a movie they have not yet watched
based on their historical ratings and the ratings of other users. In this
project we are finding out the list of most active users and most popular
movies. Also create model that finds the best suited movie for atleast two
users. The ultimate goal is to provide personalized movie
recommendations to users, improving their overall experience and
engagement with the Netflix platform.

DATA PREPROCESSING STEPS AND INSPIRATION
The preprocessing of the data include the following steps:
* Data Cleaning:
Check for null values - To remove/replace null values to increase
accuracy.
* Create a new dataset with columns cust_id, movie_id and ratings.
* Create a list containing less popular movies and less active customers
and removing them from the main dataset.
INSPIRATION: By embarking on a Netflix recommendation project, we can
gain valuable insights into user behaviour, and contribute to enhance the
streaming experience for millions of viewers worldwide.

CHOOSING THE ALGORITHM
Singular Value Decomposition (SVD) is a technique commonly used in
recommendation systems, including the one used by Netflix. It can reduce
the dimensionality of the data by keeping only the most important singular
values and vectors, allowing us to simplify the data, remove noise, and
speed up computations.

ASSUMPTIONS
* User Preferences Stability: Assuming that users preferences are
relatively stable over the short to medium term. This means that a
user's preferences for certain types of content are likely to remain
consistent over a period of time, allowing the recommendation
system to provide relevant suggestions.
* Item Popularity: Assuming that popular items are more likely to be
relevant to a larger number of users. This assumption might guide
the recommendation algorithm to give more weight to popular items
when making suggestions.
* Data Quality: Assuming that the data used for training the
recommendation model is accurate and representative of user
behaviour. This assumption underscores the importance of data
preprocessing and validation steps.

MODEL EVALUATION AND TECHNIQUES
* Root Mean Square Error (RMSE): RMSE is a commonly used metric to
evaluate the accuracy of recommendation systems. It measures the
difference between predicted ratings and actual ratings. Lower RMSE
values indicate better performance.
* Mean Absolute Error (MAE): MAE is another metric to evaluate the
performance of recommendation systems. It measures the average
absolute difference between predicted ratings and actual ratings. Like
RMSE, lower MAE values indicate better performance.
* Cross-Validation: Utilize techniques like k-fold cross-validation to
ensure strong evaluation of the model's performance. This helps in
reducing the variance of the evaluation results and provides more
reliable estimates of the model's performance.

INFERENCES
* Recommendation Quality: Evaluate the quality of recommendations
based on metrics such as Root Mean Squared Error(RMSE),Mean
Absolute Error(MAE). RMSE metrics are high indicating that the model
is effectively capturing user preferences and providing relevant
recommendations. MAE values are low indicating better performance.
* User-Item Preferences: Singular Value Decomposition helps to uncover
latent factors that represent user preferences and item characteristics.
By analysing these factors, we can gain insights into what types of
movies or TV shows are popular among different users.
* In this project, the users with cust_id’s 712664 and 2298769 are
recommended with some movies based on their ratings.
  
FUTURE POSSIBILITIES
* Deep Learning: Investigate the use of deep learning techniques, such as
neural networks, for recommendation. Deep learning models can
capture more complex patterns in user behaviour and item
characteristics, potentially leading to more accurate recommendations.
* Incremental Updates: Develop mechanisms for incremental updates to
the recommendation model, allowing it to adapt quickly to new user
interactions and feedback. This can improve the responsiveness of the
recommendation system.
* Interactive Recommendations: Implement interactive recommendation
interfaces that allow users to provide feedback and refine their
preferences. This can create a more personalized experience and
improve the accuracy of recommendations.

CONCLUSION
In conclusion, Netflix recommendation project utilizing Singular Value
Decomposition (SVD) has shown promising results in enhancing the user
experience by providing personalised movie recommendations. By
leveraging SVD, we were able to build a recommendation system capable
of generating accurate and personalised movie recommendations,
positioning Netflix as a leading provider of personalised content
recommendations in the streaming industry. The project has
demonstrated the effectiveness of recommendation systems in analysing
vast amounts of user data to generate suggestions tailored to individual
preferences and behaviours. By harnessing the power of machine learning
and big data analytics, Netflix has been able to provide users with a
curated selection of movies, thereby improving user satisfaction and
retention.
