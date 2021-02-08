# ETL-Project
# ETL-Project
#ETL-project
The focus question of that project is how the covid19 pandemic may advantage vacation takers in terms of budgeting and spending. We used 3 different datasets from the public platform Kaggle and openweather (API), which lead us to the airbnb Archive website. The data in the three files included the following information:
* Airbb_data
* Weather_data
* Cleaned_data
The fields of interest include the following:
* Hotel prices 
* Hotel rating
* Covid19 affect
* Weather within every studied city 
Transformation
In order to transform the public data and use it in our study we performed the following:
* Used Pandas functions in Jupyter Notebook to load CSV files and adding the API key.
* Reviewed the files and transformed into data frames
* Removed the operator’s column and the address column due to missing information which was not relevant to the focus of this study.
* Identified duplicates by doing an inner merge on the incident id column across all data sets.
* Created queries to address our hypothesis by grouping the hotel prices within its rating with the affect of weather data to define the high quality hotels within the price range per night under $95 . We sorted the data in descending order so we could visually see how many hotels within the studied country has high quality hotel service under $95 per night.
Load
The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame using Postgres database using PG admin to store our original clean data sets. We reconnected to the database and generated additional tables for the data frames.
Summary
There were some limitations to our findings due to the data available. However, we were able to address our hypothesis question in our initial project proposal listed in the ETL project, which taking vacation in aftermath of the Covid19 may advantage tourist in terms of budget planning. 


Group Members:
Jon Smart
Mel Sabo 
Brian Bates 
George Aziz   

