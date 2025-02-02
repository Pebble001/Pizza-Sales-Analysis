# Pizza-Sales-Analysis


### Dashboard Link :  https://acrobat.adobe.com/id/urn:aaid:sc:VA6C2:07939b03-736f-49c2-af8f-81c287c7bed8?viewer%21megaVerb=group-discover

## Problem Statement

This dashboard helps the business understand their sales pattern between the year 2009 and 2011. To provide insights to address business challenges relating to:
* Daily Sales Trend
* Hourly Sales Trend
* Best selling Pizza orders
* Lowest selling Pizza Orders


### Steps followed 

- Step 1 : Loaded data into azure data studio, dataset is an excel file.
  
- Step 2 : Opened a query page in azure data studio get some insights on the data through SQL queries
- Step 3:  Started with a union query to combine both tables together therby getting a whole look at the data across the years
- step 4:  Created a temporary table for the union table as #combinedtable
- Step 5:  Created the query for customer sementation finding recency, frequency and monetary value for all customers

<img width="857" alt="Screenshot 2025-01-15 at 10 15 54 AM" src="https://github.com/user-attachments/assets/fa84ca58-8bbc-41ae-8168-f71e3abccac2" />

- Step 7: Created a query to show how frequently products are bought across the years and the unmbers of orders mader per country.

<img width="694" alt="Screenshot 2025-01-15 at 10 23 07 AM" src="https://github.com/user-attachments/assets/2cbd346d-eece-404e-b265-7c304f143aaa" />


Step 8: Created the queries for customer segmentation into newtemporary table #RFM2


<img width="955" alt="Screenshot 2025-01-15 at 10 26 20 AM" src="https://github.com/user-attachments/assets/f188372c-078f-437f-94ff-380fdc846d73" />


<img width="1061" alt="Screenshot 2025-01-15 at 10 26 47 AM" src="https://github.com/user-attachments/assets/990174d1-a61f-41ec-ab6e-d7267c4720b4" />


- Step 9 : saved all the tables as excel files and combined all tables as different worksheet on one excel file.

- Step 10: Loaded the excel file into power BI for visualization.

- Step 11: Also since the profile will be opened only for 1000 rows by default selected "column profiling based on entire dataset".

- Step 12: Removed all errors & empty values in each column.
  
- Step 13: In the report view, under the view tab, the theme was selected.

  
- Step 14 : Total sales, total customers and total countries were respectively represented by card visuals.

   <img width="161" alt="Screenshot 2025-01-15 at 10 47 52 AM" src="https://github.com/user-attachments/assets/3da80f72-62ea-409c-b1a2-00d6cf35407e" />
  
- Step 15 : Sales by country was represented by both column chart and map. Map showed all the countries with total orders represented by dots. 

   <img width="298" alt="Screenshot 2025-01-15 at 10 49 37 AM" src="https://github.com/user-attachments/assets/b98481af-b6ad-4ba2-85c5-2ade8293876c" />

   <img width="356" alt="Screenshot 2025-01-15 at 10 50 52 AM" src="https://github.com/user-attachments/assets/0d76682d-9a7c-470d-8f0c-d465653bfc81" />

- Step 16 : Line charts were introduced to illustrate sales by quarter, sales by month and frequency of product orders.

   <img width="621" alt="Screenshot 2025-01-15 at 10 53 00 AM" src="https://github.com/user-attachments/assets/407f5eef-5856-4c70-a3ff-e356ae7b98f7" />

   <img width="245" alt="Screenshot 2025-01-15 at 10 53 10 AM" src="https://github.com/user-attachments/assets/0658465f-c908-4251-92a5-c1fab8417709" />


- Step 17 : Piecharts and donut charts represents customer segmentation, customer recency band frequency.

   <img width="531" alt="Screenshot 2025-01-15 at 10 54 51 AM" src="https://github.com/user-attachments/assets/598104ec-d3bb-4a00-9050-c810a7c0b65f" />

  <img width="250" alt="Screenshot 2025-01-15 at 10 55 00 AM" src="https://github.com/user-attachments/assets/0d5016e4-004d-461e-b660-5b6e850e70bf" />

Step 18 : Introduced slicers to interract with the visualization and show data by quarter and by year.

- Step 19 :* The analysis and visualization showed United Kindom as the country with the highest order across the years and quarters.
           * The business has a high recency as most customers made purchases recently 
           * Frequency on the other hand was low as only 3.58% of customers had a high frequency, 3.16% had good recency, 25.54% had fair frequency and a majority with 67.71% had                poor frequency.
           * High Value customers are 77.32%, seasonal shoppers 19.91% and low spenders were 2.77%.
           * Checking quarterly sales the 4th quarter of the each year was the period where most sales were recorded.
           * For Monthly sales trends month 11 'november' was the month with the highest recorded sales across the years and in both year 2010 and 2011, differs slightly in 2009                 where sales were recorded only in December.
           * The product customers ordered the most was the 'White hanging heart T-light holder', followed by 'Regency cakestand 3 tier'. The product ordered the least was 'pack 
