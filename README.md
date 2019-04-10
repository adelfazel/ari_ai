# ari_ai
This repo is created for the datascience challange on topix words

# basic archtecture 
Basic idea of machine learning is simple:
1-Train, 2-validate 3-test

# pipeline, we should set t
1- We need a function, that gets training data and returns a trained model. 
The function, internally is connected to training set data, e.g. S3 bucket or if we can get free space from google etc.

2- We will have a validation set, this validation set will give us the performance. Validation set can be used to reject a model that is worse than previous one.

3- Once satisfied, we use test set that I will leave out to see how well we are doing. 
# breakdown of the first 3 weeks. 
## week1 
1- Create a few basic functions in a main class. 
 - function train (this will return an 'empty') model that returns 50% true and 50% false 
 - obtain basic dataset and lables etc.
 - setup a basic gitlab-ci pipeline that upon commiting to 'trunk' will out a result file which shows performance of out model on a sample dataset. 

## week 2 
2- discuss avenues for data enrichment 
 - based on week1, update the train model that does to some accuracy a prediction.
 - discuss more avenues to explore. 
## week 3
- evaluate our prorgrss and decide if we have achieved initial goals, and our progrss is in the right track compared to the competion. 
