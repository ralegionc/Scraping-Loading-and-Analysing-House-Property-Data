# Scraping-Loading-and-Analysing-House-Property-Data
Scrape data, Load data and Flatten data using SQL.   
Transform data using SQL, Python, and Google Sheets.  
Analyse, Clean and build reports using SQL. 



Obtain data from bright data, download otodom poland data, and then load it into snowflake, after creating a snowflake account, download snowsql command line interface, connect to snowsql server by inputting your snowflake credentials.
Create a database and a destination table, a file format object, internal stage object.
After doing all this load the datasets into the stage(by using snowsql cli) and then load from stageg to table.

We will then convert the coordinates in our csv file to actual addresses using python code and the geopy geocoders library.
We will then again load this csv to our data warehouse snowflake, we will first create a stage and file format for it like before. This file will contain in dictionary format the address of the houses in alphabetical form. 

We will then convert polish titles to english using google sheets and google apis.
Go to google developer console, create a project and then search for google drive api and google sheets api and enable it. we will then download the keys as a json file. We will then open the translate otodom python file, put the location of the json file and the google developer email.

Then put the csv into snowflake again.

