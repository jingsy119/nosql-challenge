# nosql-challenge
## Background
### Various establishments across the United Kingdom are evaluated by the UK Food Standard Agency. The task in this challenge was to evaluate some of the food hygiene data in order to help a food magazine decide where to focus future articles.
## Language
### MongoDB was the NoSQL database used for data query and storage. All analyses were conducted in Jupyter Notebook using pymongo package in Python.
## Components
### Part 1: Database and Jupyter Notebook Set Up
- import establishments.json into MongoDB usng mongoimport command
- list the databases and collections in Mongo
- display documents in the collection
### Part 2: Update the Database
- insert data for the "Penang Flavours" restaurant into the collection
- search for BusinessTypeID and BusinessType for this type of restaurant
- update the "Penang Flavours" restaurant with correct BusinessTypeID
- delete all documents in the collection where the LocalAuthorityName is "Dover Local Authority"
- check for the removal of the Dover documents
- update latitude and longitude fields from strings to decimal numbers and RatingValue to integers
### Part 3: Exploratory Analysis (answer the following questions)
- Question 1: Which establishments have a hygiene score equal to 20?
- Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
- Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
