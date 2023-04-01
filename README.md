# misomcp
This program pulls MISO day ahead market MCPs for a specified date range

In the second cell, the dates can be edited by the user in a YYYY, MM, DD format.

This program works by generated a list of links to all of the days of interest, downloading the data from each of those links, then puts the data together into a single CSV file. 

This loop pulls the first 10 rows of data, ignoring the specifc load prices. The user can remove or edit the line in cell 4 that reads:
df = df.head(10)
According to their needs. Be careful: each year = >3000 rows if this line is removed entirely. 

Once complete, it will spit out an excel file that I personally open in excel and use "Text to Columns" to format

Reach out to jahern@strategen.com
