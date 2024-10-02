# nosql-challenge

# You will analyze food ratings data to help journalists and food critics select restaurants for future articles as per the following instructions.

Part I:

#Import the dataset from your Terminal, name the database uk_food and the collection establishments, include your import statement in your notebook in a markdown cell.
#Import dependencies, create an instance of the Mongo Client, list the databases, collections and display one document from the collection, assign the collecition to a variable.

Part 2:

# Add information provided in the instructions for the restaurant "Penang Flavors "to the database, find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only these two fields, add the BusinessTypeID to the document for Penang Flavors. 
#Find the number of documents for the Dover Local Authority, delete all of the documents with the Dover Local Authority.
#Convert latitude and longitude to decimal numbers and RatingValue to integer numbers. 

Part 3:

#Use NoSQL_analysis_starter.ipynb for this part of the challenge. 


#Convert non-numeric values to nulls. 
Answer the following questions via data analysis and perform the following actions for each question.
#Display the number of documents contained in the result, display the first document in the results using pprint, convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.



-Which establishments have a hygiene score equal to 20?

-Which establishments in London have a RatingValue greater than or equal to 4?


-What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?


-How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

Source : https://bootcampspot.instructure.com/