# PJ4_MathMetrics

This project collects the quarterly Math test scores of the students at a Texas Middle School. 
From these scores, an analysis will be performed primarily focusing on the achievement levels of two of the schools sub-populations, Black and Hispanic students. 
At the end of this analysis, we will be able to determine which Sub-Population performed the best on their quarterly tests and use this data to predict how each Sub-Population will preform on their State Assessment. 

# Prerequisites 
Requirements for the software and other tools to run:

- Tableau
- Google Slides
- Microsoft Excel
- Jupyter Notebook
- Anaconda Navigator 
- DB Browser for SQLite
  

# Getting Started
These instructions will give you a step by step method to reading and understanding the analaysis:

# Step 1- Microsoft Excel 
Student/Testing Data was acquired via the software program Edugence through gpisd.org. 
This data was then exported into CSV Excel files for usage in Jupyter Notebook.  

# Step 2- Anaconda Navigator  
Anaconda Navigator must be downloaded and installed to be able to access the Jupyter Notebook option. 
https://www.anaconda.com/products/navigator

# Step 3- Jupyter Notebook
Once Anaconda is correctly downloaded and installed, either create your own or use tbe base (root) environment to download and launch the Jupyter Notebook. 
This program launches in your default internet browser and once lauched, you can create a new "document" using the Python Programming Language. 
Python Programming language was then used to import the CSV files, convert those CSV files into Dataframes, remove the null value rows and columns, remove the columns not needed for this student, and finally merge the three CSV files into one final cleaned Dataframe that is then exported as a new CSV file named "School_Data.csv". 

# Step 4- DB Browser
DB Browser must be downloaded and installed. 
A new Database was created and the "School_Data.csv" file was imported and used the query calculations on the data. 
These calculations were the foundations of the visuals that are being displayed in Tableau. 
https://sqlitebrowser.org/dl/

# Step 5- Tableau
The free version of Tableau must be installed. 
Tableau was used to convert the "School_Data.csv" file into multiple visuals. 
Workbooks, Dashboards and the Story features were used in this Project. 
https://www.tableau.com/

# Step 6- Google Slides

# Running the tests
Explain how to run the automated tests for this system

# Contributors
- Students of DATA @ Adams Middle School in Grand Prairie, TX
- Math Test writers of the Grand Prairie ISD
- Patrick Carpenter

# Authors
- Patrick M Carpenter

# Acknowledgments
The following reasources were used to assist me with the completion of the project in multiple ways: 

- A.I. through Microsoft CoPilot and Google Chrome
- ReadMe Template by Billie Thomposon
- ChatGPT
