In this project we took raw job market data and trasnformed it using MySQL to make it more usable for analytics.

Skills used:
  Removed Duplcate Data:
    Used CTE, Windows Function, and a New Table to label duplicate data with a row number and then deleted all rows with the duplicated row number
  Standardized Data:
    Changed strings into dates
    Created a standard for all dates in our table
    Used Trim() to remove leading "..." and spaces
  Removed Null/Blank Values
    Used Self Joins to discover Null Values and removed them by altering the table
  Removed columns that weren't necessary
    Used drop "drop column" to remove a column we created to find duplicate data
    
    
