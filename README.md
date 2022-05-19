# Movies-ETL
## Purpose

Amazing Prime is having a Hackathon. I have assisted Britta with creating a automated pipeline. This pipeline will take new data,perform the appropriate transformations, and loads data into existing tables. The objective of this project was to to create a pipeline using the Extract,Transact,and Load(ETL) automated process. This process was completed on the kaggle.com movie dataset and Wikipedia. We then take this information and create the tables needed.


## Deliverable 1: Write an ETL Function to Read Three Data Files
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.

### Wiki_movies_df
<img width="946" alt="image" src="https://user-images.githubusercontent.com/101374716/169411763-1d2cdbab-8dcb-4c25-8df6-71e55fe1964d.png">

### kaggle_metadata
<img width="997" alt="image" src="https://user-images.githubusercontent.com/101374716/169411503-02ff2e91-4291-4e40-828d-80a609cd2a41.png">

### Ratings
<img width="258" alt="image" src="https://user-images.githubusercontent.com/101374716/169411900-cc1668ce-0e70-4ce2-8713-81b827dd7e9c.png"

## Deliverable 2: Extract and Transform the Wikipedia Data
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

### wiki_movies_df
<img width="963" alt="image" src="https://user-images.githubusercontent.com/101374716/169412519-39c483aa-0899-4926-a54e-ed0a047f57a6.png">

### wiki_movies_df.columns.to_list()
<img width="496" alt="image" src="https://user-images.githubusercontent.com/101374716/169412679-0c3ba73c-9419-41ac-818e-206b37b24148.png">

     
## Deliverable 3: Extract and Transform the Kaggle data
Merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

### wiki_movies_df
<img width="976" alt="image" src="https://user-images.githubusercontent.com/101374716/169413239-e98e2b42-47e8-431e-a909-edb3e5fd3e65.png">

### movies_with_ratings_df
<img width="998" alt="image" src="https://user-images.githubusercontent.com/101374716/169413157-27e63b8b-1f2b-4a36-81a3-88b82a9c8528.png">

### movies_df
<img width="992" alt="image" src="https://user-images.githubusercontent.com/101374716/169413060-400168aa-3f4d-48da-bdef-31090215c0e3.png">

Merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

## Deliverable 4: Create the Movie Database
### Movies Database
<img width="873" alt="image" src="https://user-images.githubusercontent.com/101374716/169413688-21a909e2-78b3-4bb7-be62-2a8952bea6ce.png">

### Rating Database
<img width="465" alt="image" src="https://user-images.githubusercontent.com/101374716/169413764-126ec2f4-3162-48b1-9edd-34d19262d277.png">


