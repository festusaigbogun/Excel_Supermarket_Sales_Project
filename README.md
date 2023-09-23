# INTRODUCTION  
The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. **The data is gotten from keggel**

## SKILL DEMONSTRATED
- Using Power query editor
- Using Conditional Formatting 
- Using Pivot tables
- Using different charts for making visualization 
- Making use of some Excel functions 
- Identifing KPI's
- Making use of DAX formula to calculate new measure 

### BUSINESS QUESTIONS 
- What CITY have the highest sales and profits 
- What branch have the highest sales and profits 
- What TIME do they normally have high sales
- What PRODUCT LINE have the highest PROFIT and which one is the lowest
- Percentage of PAYMENT METHOD used by customers 
- The MONTH with the most sales
- Gender by the count of Product line purchase 
- PRODUCT LINE with the most TAX payment 
- Count of Customer type

#### DATA CLEANING 
So after opening the file on a Excel worksheet I checked for if there was missing values or data errors on the dataset and discovered none. Then I proceeded with checking if there are duplicates values on the dataset, and also discovered none. 

##### DATA ANALYSIS 
Using the **Ctrl+T** shortcut key i was able to create a table for the dataset. The advantage of creating a table is that it helps create a column header and filter, make the dataset virtually appealing, for easy sorting and aggregation and lastly, tables work well with Excel's data visualization tools, like pivot tables and pivot charts which allow one to analyze and present data more effectively. 

Now the dataset now  consists of the Invoice ID, Branch, City, Customer type, Gender, Product line, Unit price, Quality, Tax5%, Total, Date, Time, Payment, Cogs, Gross margin percentage and Rating columns. 

I used the conditional formatting on the **RATING** column to give rating which is above 5.0 the green up arrow sign and the rating which is below 5.0 a red down arrow sign. While the Rating that is exactly 5.0, it was given a yellow straight arrow (but in this situation there is no rating having the exact 5.0 rating). 

###### PIVOT TABLE
Next I created pivot table where business objectives are being answered. I was also able to use the DAX formula to calculate the PROFIT column, by subtracting the sum of TOTAL column by the sum of QUALITY column. 


I was also able to get the KPI's for this analysis using the Pivot table


#### BUSINESS OBJECTIVES SOLUTION 
**WHAT CITY AND BRANCH HAS MOST TOTAL SPENDING**
The results is shown in the pivot table and chart below:

WHAT TIME DO THEY NORMALLY HAVE HIGH SALES
The results is shown in the pivot table and chart below:

WHAT PRODUCT LINE HAS THE HIGHEST PROFIT AND WHICH ONE IS THE LOWEST 
The results is shown in the pivot table and chart below:

PERCENTAGE OF PAYMENT METHOD USED BY CUSTOMERS 
The results is shown in the pivot table and chart below:

THE MONTH WITH MOST SALES
The results is shown in the pivot table and chart below:

PRODUCT LINE BY GENDER
The results is shown in the pivot table and chart below:

PRODUCT LINE WITH THE MOST TAX PAYMENT 
The results is shown in the pivot table and chart below:

PRODUCT LINE BY UNIT PRICE 
The results is shown in the pivot table and chart below:


