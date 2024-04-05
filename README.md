# Data_Wrangling_PR2

## Build your ETL pipelines with Dags

### Extract: copy data from source into your compute engine.
The data can only be accessed after the IRB approval. It was stored in box, so I identify the base directory.
### Transform: transform the data to its desired state.
Done.
### Load: load the data into your data warehouse.
Saved to box or my PC.

### DAG - directed acyclic graph (from E to L)
See figure: PR2_Yuyi.png
This was made by tools: https://www.dagitty.net/dags.html#


## Rubric (100 points max):
### Combine same variables across all csv files.
1. Built a function to combine CSV files of the same type.
2. And save each combined dataframe to a new CSV file. Run it.
### Split the location data to different columns
3. Define a function that converts the JSON string into a Python dictionary, and apply the function to the 'CAST(data as CHAR)' column.
4. Convert the resulting series of dictionaries to a DataFrame.
5. Concatenate the original DataFrame with the new columns from JSON.
6. Save the resulting DataFrame to a new CSV file.
### Get the top 5 locations for each participants
7. Build a function to check if all intervals are the same for each group, and apply it.
8. Print out the result to check.
9. Define a function to get the top 5 locations for each group, and apply the function to each participant's group of data.
10. Clean up the index and leave `Prefix` as a column.
11. Save the top_5_locations_each_person DataFrame to a CSV file.
12. Define a function to reverse geocode.
13. Use an example to test the function.
14. Create new columns for address and category, and run the function.
15. Print completed and save the updated dataframe to a new CSV file.
16. Count the number of occurrences of each category.
17. Convert the Series to a DataFrame for easier handling.
### Self-Reported Location Prepossing
Some tests and cell outputs have been cleaned before uploaded to github because of data privacy issue in this part. However, I believe the functions and comments are clear enough to understand.

## Please submit an estimate of distribution of work in README.
I did this work by myself.
