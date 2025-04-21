# data-analytic-day-1
Repository for submitting task on netflix and tv show data. 
In this task I did data preprocessing on the dataset Neflix and TV shows ratings. 
First I checked for datatypes, duplicate values and null values. 
Then I replaced the null values with mode of the other values in the column(for rating, duration, country), 
or replace the null values with the value'unknown'(for director, cast). 
Lastly I removed some of the rows eith null values. 
Next I standardised text values so that they are all in lower case and withour extra spaces. 
Next step envolved normalizing country names (United states: usa, united kingdom: uk, ...). 
Converted Date Formats to Consistent Type (september 25, 2021 -> 2021-09-25). 
Sorting the values of 'rating' into 3 categories of kids, teens, adults. 
Showing the final table using df.head(). 
