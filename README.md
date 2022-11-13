# -Movies-ETL
#Project Overview
Within the scope of the Amazing Prime Hackathon, this project will create an automated pipeline that takes in new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data.
# Results
#Write an ETL function to read three data files
The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.

#Extract and Transform the Wikipedia data
We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

#Extract and Transform the Kaggle and rating data
Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
![image](https://user-images.githubusercontent.com/108849308/201543881-f516e1a4-16b4-4ea3-82b1-07db83c9873c.png)
