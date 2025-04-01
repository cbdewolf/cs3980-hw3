# cs3980-hw3

## Overview

The goals of this assignment are to setup the MongoDB Atlas, install MongoDB Community Edition, and run queries in the MongoDB Compass.

### Assigned Work

The assigned work for this HW are as follows:

- Signup for MongoDB Atlas
- Install MongoDB Community Edition
- Run queries in MongoDB Compass
  Once the registration and setup are completed, we are assigned to complete a few queries to demonstrate our understanding of writing queries to retreive data from the sample set "sample_mflix"

## The Queries

### 1)

The first query we were told to write was to find all movies with a runtime greater than 200 minutes in the year 1983, with the movies sorted by increasing runtime. We are also to only display the following fields: runtime, title, and year.
Here is the query I made with its result:
![image](https://github.com/user-attachments/assets/908ab370-317b-4b19-a091-20e0e6c1ce10)
The first argument in find() will actually get the movies with the desired criteria, the second will ensure the only fields in the output are the desired ones. I also added a .sort() method on the end to ensure that it would be ordered in increasing runtime.

### 2)

The second query we were told to write is to find all movies that came out after the year 2014, with an IMDb rating greater than 9.
Here is the query and its result:
![alt text](image.png)
Once again, we use a find() to get the result. The first argument will get only the movies of the queries requirements, and the second will only show the fields that were requested. Also, I sorted the movies on decreasing rating in order to get the desired order in the sample output.
