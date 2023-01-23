# misomcp
Pulls MISO day ahead market MCPs for a specified day range

This is a jupyter lab file, easiest for me to use but you can apply the same logic to any applicaiton you like.

The loop pulls the first 12 rows of data, ignoring the specifc load prices. Be careful: each year = >3000 rows 

Once complete, it will spit out an excel file that I personally open in excel and use "Text to Columns" to format, although you can probably do it better / faster 
in python. 
