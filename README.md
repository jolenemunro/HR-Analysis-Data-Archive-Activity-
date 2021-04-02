# HR-Analysis-Data-Archive-Activity-
Assignment for DATA1282 Data Archive Activity

The problem determines the number of salespeople with or without attrition, and their average, minimum and maximum monthly income. It also counts the number of salespeople with and without attrition within various monthly income levels. 

The insights provided that just over 3/4's of the salespeople are without attrition and while some make a higher monthly income, overall the monthly income distribution is similiar to salespeople with attrition. Most salespeople fall in the $5000/month income range.

The directory structure contains the following folders: 
Data - URL to Kaggle website for'IBM HR Analytics Employee Attrition & Performance' csv data file 
Munge - HDInsight transformation steps applied to the csv data to extract salespeople, attitrition and monthly income data
Src - contains aggregations, i.e. avg, min, max of monthly income, applied to the data
Reports - contains visualizations of a histogram comparing the monthly income for salespeople with and without attrition, and a dashboard for the count of salespeople with and without attrition.
