### <center>Movie Recommendation System</center><center>How to Write Fast Code team032 term project abstract</center>
###### <center>Shuo Huang, Hongchen Xie, Lin Liu</center>

#### Description of problem

<p style = "margin:0px" >In real life movie watching website, movies are recommended for different people based on their rating on movies they have watched. We can use Hadoop on vast data to help people find movies to their taste. </p>

#### Description of solution

##### Dataset

<p style = "margin:0px" >The dataset is on MovieLens. We will use three size of dataset for our training and testing. They are 100K Dataset, 1M Dataset and 10M Dataset. In every dataset, each line is formatted as: </p>

<p style = "margin:0px" ><center>user id | item id | rating | timestamp</center> </p>

- **user id**: Total 1000 users in 100K Dataset. Total 6000 users in 1M Dataset. Total 72,000 users in 10M Dataset.
- **item id**: Total 1700 movies in 100K Dataset. Total 4000 movies in 1M Dataset. Total 100,000 tag applications applied to 10,000 movies in 10M Dataset.
- **rating**: Total 100,000 ratings in 100K Dataset. Total 1 million ratings in 1M Dataset. Total 10 millions ratings in 10M Dataset.

##### Model selection

<p style = "margin:0px" >Collaborative filtering (CF) is a technique used by recommender systems. Collaborative filtering is a method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating).
The underlying assumption of the collaborative filtering approach is that if a person A has the same opinion as a person B on an issue, A is more likely to have B's opinion on a different issue than that of a randomly chosen person. For example, a collaborative filtering recommendation system for television tastes could make predictions about which television show a user should like given a partial list of that user's tastes (likes or dislikes). Note that these predictions are specific to the user, but use information gleaned from many users.</p>

<p style = "margin:0px" >Based on collaborative filtering, we plan to use MapReduce, Hadoop with Pig and Hadoop with Spark to speed up.</p>

##### Model evaluation

For accuracy, we plan to use Root Mean Square Error(RMSE) to computer the error of each model.

#### Outline of Expectation and Improvements

- Accuracy: Our expectation on applying the best model to the test dataset is about 80% closed to the ground truth.
- Total training time: We plan to apply collaborative filtering based on MapReduce, Hadoop with Pig and Hadoop with Spark and compate their training time.

#### Timeline

1. Term Project Abstract: March 30th
2. Implement on a single computer based on 100K dataset: April 7th
3. Implement on Hadoop based on 1M dataset: April 14th
4. Implement on Spark based on 10M dataset: April 21th
5. Term Project report: April 28th


