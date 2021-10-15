This Assignment uses pandas to import and explore the raw data of the Baseball Databank's Teams supplemental data table.

Using pandas, I show the shape of the dataframe (the number rows and colums), the names of the columns, and the data type of each of the 48 columns.

df.info() also shows the data type of each column, as well as the # of rows in each column that does not have a NULL value.

I then show the first 13 rows of the dataframe followed by the last 9 rows.

Lastly, I explore the data using different groupings. First I group the data by teamID and show the average Runs allowed. Then grouping by year and division, I explore the mean Wins, Homeruns, and completed games. And finally, grouping by Division, I explore the number/names of different home ballparks.