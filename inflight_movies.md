# In-flight entertainment system

Imagine that you are working for an airline company. 
Lately they are receiving complaints from their customers regarding the in-flight entertainment system.
The issue is that for the longer flights users would like to start a second movie when their first one ends, but the plane usually lands before they can see the ending.

**Your task is to build a feature that will choose 2 movies whose total time is equal with the exact flight length.**

Your feature will have 2 input parameters:

* the fligth length in minutes
* an array of integers that represents the time in minutes for each movie

The output should be a boolean that will indicate if there are 2 movies whose sum equals the flight length.

When building the feature:

* assume that the user is watching exactly 2 movies
* user should not watch the same movie twice

**OPTIONAL:** What if we wanted to fill the flight length as nicely as possible with any number of movies (not just 2)? 
