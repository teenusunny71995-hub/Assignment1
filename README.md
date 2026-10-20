**EXCEL ASSIGNMENT 1**

1. Sum, Count, Average:
Total price of all products in the dataset found using sum fucntion [=SUM(D2:D35)]
Number of products in the dataset found using CountA function since products are in text format [=COUNTA(B2:B35)] 
Average price of products using Average function [=AVERAGE(D2:D35)]

2. Min and Max:
Minimum price among all products found using Min function [=MIN(D2:D35)]
Maximum price among all products found using max function [=MAX(D2:D35)]

3. IF Function:
Created a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
The formula used is [=IF(D2>=500,"High Price","Standard Price")]

4. SUMIF and COUNTIF:
 Total price for products in the 'Electronics' category calculated using the SUMIF function [=SUMIF(F2:F35,"Electronics",D2:D35)]
 The count of products with a price less than $100 using the COUNTIF function [=COUNTIF(D2:D35,"<100")]

5. Text Formatting - LEFT, RIGHT, MID:
Day column has been created and first 2 characters of each 'Product ID' captured using the LEFT function [=LEFT(A2,2)]
Country Code column has been created and the last 2 characters from the 'Product ID' column captured using the RIGHT function [=RIGHT(A2,2)]
Month column has been created and extracted 4th to 6th characters from the 'Product ID' column using the MID function [=MID(A2,4,3)]
