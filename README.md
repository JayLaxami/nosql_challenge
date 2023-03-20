# nosql_challenge

This assignments contains Resources folder with a json file called 'establishmments'

uk_food database is created with collection name 'establishments' and jason file is added to it.

Starting with NoSQL setup starter jupyter notebook- connection is created between database and server.

Document is reviewed in collection to make sure connection is established.

UPDATE DATABASE----

In this, new restaurant "Penang Flavours" is inserted to the database.

This new restaurant is updated with Business ID.

Total documents are counted for Local Authoriy name as "dover" which was deleed from the documents.

Longitude and Latitude data tyoes were changed from String to Decimal values.

In NoSQL analysis jupyter notebook, all the dependencies and connections are established just like setup notebook.

Different query were established in this and their reults were converted to pandas DataFrame.

First query : Hygiene score equal to 20 and dataframe of this query is named as - 'establishment_df'.

Total number of rows in this DataFrame(establishment_df) is 41.

Second query : Establishments in London have a 'RatingValue' greater than or equal to 4 and dataframe for this is - 'new_df'.

Total number of rows in this DataFrame(new_df) is 34.

Third query was about finding top 5 establishments with a 'RatingValue' rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours" and for this dataframe is named as 'top_df'.

Last query is about establishments in each Local Authority area have a hygiene score of 0.  In this, pipeline is created with match and group query and aggregate function is used in this. First 10 results were printed with sorting from highest to lowest.
In this, dataframe is named as 'pipeline_df' and total number of rows in the DataFrame is 55.
