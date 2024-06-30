# Crowdfunding Analysis

## Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s.
From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success.
In this project will be organized and analyzed a database of 1,000 sample projects to uncover any hidden trends.

## Data sources
- [CrowdfundingBook.xlsx](CrowdfundingBook_Walgama.xlsx)

## Tools used
- Data cleaning and preparation.
  - Conditional Formating to color the cell background.
  - Basic mathematical formula to calculate sum and averages. 
  - IFERROR() function to handle the null values. 
  - Date conversion functions. 
  - TEXTBEFORE() function to split the columns to multiple columns. 
- Data Analysis
  - Power Pivot (Pivot Table).
  - Add filters to pivot table to filter data.
  - Use statistical functions (SUM,AVERAGE,MEAN,MEDIAN,MAX,MIN,VAR.P,STDEV.P) to generate the summary values. 
  - Box & Whisker chart to identify the outliers.
  
## Exploratory Analysis
- Count the number of records for a given criteria. 
- Search data with aggregation.
- Sort and limit the search results data. 
- Store  the results data in a pandas DataFrame.

# Folders and files.
- Root folder
  - [CrowdfundingBook_Walgama.xlsx](CrowdfundingBook_Walgama.xlsx)
 
- Analysis folder
  - [establishments.json](Resources/establishments.json)

- Summary folder
