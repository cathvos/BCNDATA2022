
# Lab | Tableau -Aggregating Profitability

Build the following charts making use of the date parts/values in tableau and publish them to your tableau public account in order to submit the url via the Student Portal

## Your Challenge

Using the data set [global_superstore](https://github.com/student-IH-labs-and-stuff/BCNDATA0122/blob/main/Labs/Tableau/Global%20Superstore.xlsx) with the Orders table and Tableau Public, create the following charts to visualise:

(Ensure each chart has the appropriate fit, chart/mark type, title, axis labels and colour scheme.)


1. Overall Profitability over time by market - using Year, Quarter data values (green fields)
2. Overall Profitability by Sub category - with Category, Date, Market filters
3. Average Profit per unit (using a calculation of profit divided by quantity) with a filter for Category and Subcategory (link your filters using only relevant values)
4. Profitability by Country (as a filled map) with a market filter but also with a clever % of total label created from an LOD.
 By using a FIXED LOD on the text label, we hope to see the global contribution to the company profit from each country- ie how much of the profit does Germany account for  - in this way the % of total profit label is unaffected by the filters when applied). Bonus, try adding a simple bar chart viz embedded in the tool tip of the map, similar to that created in Step 2, so that when you hover over a country you can see the profitability in that country by product category
6. Create a highlight table or any other chart type to quickly see the profit pattern between weeks and days of the week, with profit ratio % (profit divided by sales amount) on colour - be careful with your aggregation approach, remember to pre-aggregate! 

BONUS 7. Create a stacked 100% bar view showing the % of transactions which were profitable within each category and subcategory. Hint: you will need a table calculation at the cell level, but you will want to use a non aggregated calculation for profit> 0 so that the logic is applied at the row level. 


----- proprietary content of SED Training Ltd-------