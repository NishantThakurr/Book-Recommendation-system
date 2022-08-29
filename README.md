
# Book Recommendor system

It's a book recommendation system which shows the top 4 recommendations for a particular book which uses collaborative filtering for the task.


## Demo


https://user-images.githubusercontent.com/102639991/187241901-4fe1fa6c-0bdb-40db-8d0d-a3f6ded27de0.mp4

## Roadmap

Part 1
CREATING A TOP 50 books library for the front page of application
Step1:

Importing the relevent libraries and loading the relevent 
datasets.

![image](https://user-images.githubusercontent.com/102639991/187234605-318bff5e-c4b5-4062-ad7b-b374cd9606cb.png)

Step2:

Using merge to join the different datasets.
(Just like JOIN in SQL)

![image](https://user-images.githubusercontent.com/102639991/187235276-9202f0c6-e176-4de4-be17-9799b08db6c7.png)

Step3:

Filtering books with at least 250 no of ratings by 
group by 
(Similar to GROUP BY in SQL)
![image](https://user-images.githubusercontent.com/102639991/187236468-ab715011-cb4f-4ed6-b316-3751d4825fe8.png)

Step4:

Trying to find average ratings of the books by 
group by 
(Similar to GROUP BY in SQL)
![image](https://user-images.githubusercontent.com/102639991/187236915-0fbca2f0-fc06-4d77-850e-ba9f2af78998.png)

Step5:

Merging the average rating dataframe with at least 250 no of ratings datasets and Filtering out the top 50 books based on average ratings

Step6:

![image](https://user-images.githubusercontent.com/102639991/187238053-d088bf27-f115-4c9e-94c3-cd2069cc4105.png)

Step 7:

Collaborative Filtering:
Collaborative filtering is a technique that can filter out items that a user might like on the basis of reactions by similar users. It works by searching a large group of people and finding a smaller set of users with tastes similar to a particular user.

Step 1: First only regular users are filtered out(Users with at least 250 ratings)
![image](https://user-images.githubusercontent.com/102639991/187239091-0106728b-da66-4c85-9bbf-ae9057a17513.png)

Step 2:

Filtering books with at least 50 ratings

![image](https://user-images.githubusercontent.com/102639991/187240075-7d14967c-47f7-4b4b-b009-e361fdeab780.png)

Step3:
Creating a pivot table for Collaborative Filtering

![image](https://user-images.githubusercontent.com/102639991/187240226-388c0db8-136d-4c0c-91c9-d1ff3cdbbef7.png)
![image](https://user-images.githubusercontent.com/102639991/187240298-43a1b2fb-b712-47a9-863f-35372754e5ac.png)

Step4:

Creating a function using cosine similarity to recommend new books
and dumping these dataframe as pkl for creating an app in Pycharm

Part 3 Working with Flask in Pycharm 

It involved creating a main python project in Pycharm with some html templates










