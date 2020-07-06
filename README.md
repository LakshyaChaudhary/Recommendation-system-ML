# Recommendation-system-ML


Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user. These systems have become ubiquitous can be commonly seen in online stores, movies databases and job finders.
In this model, i have build a recommendation systems based on Collaborative Filtering and implement simple version of one using Python and the Pandas library.


Collaborative Filtering :-


The first technique we're going to take a look at is called Collaborative Filtering, which is also known as User-User Filtering. As hinted by its alternate name, this technique uses other users to recommend items to the input user. It attempts to find users that have similar preferences and opinions as the input and then recommends items that they have liked to the input. There are several methods of finding similar users (Even some making use of Machine Learning), and the one we will be using here is going to be based on the Pearson Correlation Function.



The process for creating a User Based recommendation system is as follows:

1. Select a user with the movies the user has watched
2. Based on his rating to movies, find the top X neighbours
3. Get the watched movie record of the user for each neighbour.
4. Calculate a similarity score using some formula
5. Recommend the items with the highest score



Advantages and Disadvantages of Collaborative Filtering :-


Advantages -

* Takes other user's ratings into consideration
* Doesn't need to study or extract information from the recommended item
* Adapts to the user's interests which might change over time

Disadvantages -

* Approximation function can be slow
* There might be a low of amount of users to approximate
* Privacy issues when trying to learn the user's preferences

