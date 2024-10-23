# Assignment_Two
You can see the code here [here](file:///Users/dftorres/Documents/GitHub/DPP690/Assignment_Two/index.html)

Cleaning LEAD dataset 

I examined the dataset for missing data. I found NAs and the type of data. I then determined that the NA was in the year column for a country. This was likely an error in the dataset. I made sure there were no whitespaces in the Country column. The data was mostly clean, so I saved it as a CSV file. 

Formatting LEAD dataset
I imported the saved file and edited the column names, selected a group of columns, and filtered for a specific countries (EU, USA, Canada, Australia, Japan, S Korea, and New Zealand) and years (2003-2020). 
I saved the formatted LEAD dataset as a CSV file. 

Cleaning Freedom House Dataset_2 
I examined the Freedom House Dataset 2 and noticed cleaning issues. Several columns of data where character when it should hae been numeric. So I used GREP to determine what were the non-numeric data. Almost all of the data was "-" "-1" so I was able to mutate them into numerics. I also made sure the Country column didn't have any whitespaces.  I checked the columns to make sure it was corrected and saved it as CSV file. 

Formatting Freedom House Dataset_2 
I imported the CSV, changed the "Country/Territory" column to Country and Renamed each column. I eliminated the "C/T" column and filtered the dataset for countries (EU, USA, Canada, S Korea, Japan, Australia, New Zealand) and years (2003-2020) 

Cleaning Freedom_House Dataset
I noticed the data was mostly clean and character and numeric columsn were correct. No real cleaning was needed so I aved the file. 

Formatting Freedom_House Dataset 
I load the CSV file and renamed the columns, selected the columns that I wanted to use, filtered for the countries (EU, USA, Canada, S Korea, Japan, Australia, New Zealand) and years (2003-2020). I doubled checked all of the columns at the end and saved it.  
