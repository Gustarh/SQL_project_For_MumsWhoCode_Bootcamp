Fill out this file with a description of the issues that will be addressed by cleaning the data if there are any
Include the queries used to clean the data
Explore the data to reveal shape, patterns and its overview 

Data Quality Issue was identified in the Airbnb Table Dataset. Below is a summary of the data quality issue:

1. Duplicate Values. Duplicates Values were removed using this Syntax:
 SELECT DISTINCT(*) FROM listings

2. Deleted Amenities and host_verification Column as they are irrelevant and redundant to the analysis respectively. Syntax:
i.ALTER TABLE listings
DROP COLUMN amenities
ii.ALTER TABLE listings
DROP COLUMN host_verification

Data Exploration,
After the cleaning of the anomalies and inconsistent data, the dataset is left with 39 columns and 21120 rows


			


