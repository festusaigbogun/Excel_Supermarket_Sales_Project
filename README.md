# INTRODUCTION  
The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. **The data was gotten from kaggle**

## SKILL DEMONSTRATED
- Using Power query editor
- Using Conditional Formatting 
- Using Pivot tables
- Using different charts for making visualization 
- Making use of some Excel functions 
- Identifying KPI's
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
- PRODUCT LINE by the sum of COGS

### DATA CLEANING 
After opening the file in an Excel worksheet, I conducted an initial assessment to identify any missing values or data errors in the dataset, but none were found. Subsequently, I performed a check for duplicate values in the dataset and likewise found none.

### DATA ANALYSIS 
By utilizing the Ctrl+T shortcut key, I generated a table for the dataset. The benefits of this approach include the automatic creation of column headers and filters, enhancing the dataset's visual appeal for effortless sorting and aggregation. Furthermore, tables seamlessly integrate with Excel's data visualization tools, such as pivot tables and pivot charts, facilitating more effective data analysis and presentation. As a result, the dataset now encompasses the following columns: Invoice ID, Branch, City, Customer type, Gender, Product line, Unit price, Quantity, Tax5%, Total, Date, Time, Payment, Cogs, Gross margin percentage, and Rating.
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_30TTRhz0MA.png) 

I applied **conditional formatting** to the 'RATING' column, assigning a green upward arrow to ratings above 5.0 and a red downward arrow to ratings below 5.0. In the unique case of a rating exactly at 5.0, a yellow straight arrow was designated, although there were no instances of a precise 5.0 rating.

![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_Sw7RvHzNCR~2.png)  ![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_oMUeMfFe5u~2.png) 

By leveraging **Power Query Editor**, I successfully transformed the TIME column from a **Decimal Number** format to **Time** format. This transformation was crucial to prevent Excel from interpreting the time column as standard decimal values. Additionally, I converted the DATE column from **Date/Time** format to a more conventional **Date** format. Utilizing Power Query Editor allowed me to ensure that all columns were correctly formatted as needed.

![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_uiwJlR3GU7~2.png) ![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_wNyh8CU57e~2.png) 

![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_CrRR5Ip2Wa~3.png) ![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_bWTXkcW2ne~2.png) 

#### PIVOT TABLE
Next, I generated a pivot table to address all the business objectives, and I effectively employed the **DAX formula** to compute the 'PROFIT' column by subtracting the sum of the 'TOTAL' column from the sum of the 'COGS' column.
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/nKF6mQO0lR~2.png) 


I was also able to get the KPI's for this analysis using the Pivot table
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_TCgG5kTvRL~2.png) 


#### BUSINESS OBJECTIVES SOLUTION 
**WHAT CITY HAVE THE HIGHEST SALES AND PROFIT**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_TCgG5kTvRL~3.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_pMmqJRwwvb~2.png) 

**WHAT BRANCH HAVE THE HIGHEST SALES AND PROFIT**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_1SkOnw8TRC~2.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_OVHVMsXPox~2.png) 

**WHAT TIME DO THEY NORMALLY HAVE HIGH SALES**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_dmuadDSbfq~2.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_f9ZdBP5Usv~2.png) 

**WHAT PRODUCT LINE HAVE THE HIGHEST PROFIT AND WHICH ONE IS THE LOWEST**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_TCgG5kTvRL~5.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_3bCqpIFkmB~2.png) 

**PERCENTAGE OF PAYMENT METHOD USED BY THE CUSTOMERS**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_dmuadDSbfq~3.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_wN6AJ9524D~2.png) 

**THE MONTH WITH THE MOST SALES**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_RAJrnjZchO~2.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_19k3MnsAbc~2.png) 

**GENDER BY THE COUNT OF PRODUCT LINE PURCHASED**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_nKNlXJWsyo~2.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_05FsHHKRSw~2.png) 

**PRODUCT LINE WITH THE MOST TAX5% PAYMENT**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_nKNlXJWsyo~3.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_RAJrnjZchO~3.png) 

**COUNT OF CUSTOMER TYPE**

The results is shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_nKNlXJWsyo~4.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_v1AxMJ2sXk~2.png) 

**PRODUCT LINE BY THE SUM OF COGS**

The results in shown in the pivot table and chart below:
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_1SkOnw8RRR~2.png) 
![](https://github.com/festusaigbogun/Excel_Supermarket_Sales_Project/blob/main/Images/EXCEL_xMdn7QDG36~2.png) 



#### INSIGHTS 
1. **Sales and Profits by City:**
   - Naypyitaw stands out as the city with the highest sales and profits, whereas Mandalay lags behind in both sales and profitability.

2. **Profitable Product Line:**
   - Among the various product lines, "Food and Beverages" emerges as the most profitable, while "Health and Beauty" ranks as the least profitable.

3. **Sales and Profits by Supermarket Branch:**
   - Supermarket Branch C leads in both sales and profitability, whereas Branch B reports the lowest figures for both sales and profits.

4. **Peak Sales Hours:**
   - Sales peak at 19:00 hours, with a noticeable decline by 20:00 hours.

5. **Monthly Sales Performance:**
   - January records the highest sales, closely followed by March, with February marking the month with the least sales.

6. **Gender Preference for Product Line:**
   - The female demographic displays a preference for purchasing products from the specified product line.

7. **Customer Type Distribution:**
   - Membership customers outnumber normal customers.

8. **Preferred Payment Method:**
   - Ewallet emerges as the preferred payment method, used more frequently than any other payment option.

  ### RECOMMENDATION
Based on the insights from the dataset, I recommend the following business actions:

1. **Focus on Naypyitaw and Supermarket C**:
   - Allocate more resources and marketing efforts to Naypyitaw, where you have the highest sales and profits.
   - Pay special attention to Supermarket C branch, as it is your top-performing branch. Consider replicating its successful strategies in other branches.

2. **Optimize Product Lines**:
   - Given that Food and beverages are your most profitable product line, consider expanding your offerings in this category and promoting related products.
   - Reevaluate your Health and beauty product line to improve its profitability or consider reducing its prominence.

3. **Time-Based Sales Strategy**:
   - Since sales peak at 19:00 hours and drop by 20:00 hours, plan your inventory, staffing, and promotions to make the most of this prime selling time.

4. **Seasonal Sales Strategy**:
   - Capitalize on the high sales in January and March. Plan special promotions and marketing campaigns during these months.
   - Offer promotions or loyalty programs in February to boost sales during the typically slower period.

5. **Target Female Shoppers**:
   - Given that females make more purchases in your stores, tailor your marketing efforts to cater to their preferences and needs.

6. **Membership and Ewallet Promotion**:
   - Since there are more Member customer types and Ewallet is the preferred payment method, incentivize customers to become members and use Ewallet by offering exclusive discounts or rewards.

7. **Mandalay Branch Improvement**:
   - Analyze the underperforming Mandalay branch to identify issues causing lower sales and profits. Implement strategies to improve its performance.

8. **Continuous Data Analysis**:
   - Keep analyzing your sales data regularly to identify trends and make data-driven decisions.

9. **Customer Feedback**:
   - Gather feedback from customers to understand their needs and preferences better, and use this information to improve your products and services.

10. **Cost Management**:
    - Continuously monitor costs and expenses to ensure that your profits remain healthy even in the most profitable areas.




