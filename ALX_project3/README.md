# Prosper Loan Data Exploration
## by Naomi Ayibaemi Frank-Opigo


## Dataset
This dataset contains borrower data and loan data for 113937 loan listings in the USA. 

#### Dataset structure
There are 113,937 loan entries with 81 details each. The data types include : floats, integers,datetime, categorical, boolean and string. Most variables are numeric. 

#### Preliminary wrangling
Aftter loading the dataset into the dataframe named "loan", some wrangling was carried out to make the data suitable for exploration. These include:
1. Conversion of Listing creation date ,Closed date, First recorded credit line and Loan origination date columns to date-time data.
2. Extraction of year and quarter from the Listing creation date column into separate columns name "Year" and "Quarter" respectively,
3. Conversion of Loan status, Prosper Rating (numeric), Prosper Rating (Alpha), Prosper Score, Listing Category (numeric), Loan Origination Quarter,Income Range and Quarter columns to categorical data.
4.Conversion of Listing Number column to string data.

## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

1. Loans of higher amounts have a lower borrower count
2. The most popular loan amount is 4,000 USD
3. Borrowers are more often home owners, especially those with higher prosper scores.
4. Higher income earners access higher loan amounts
5. Annual loan amounts have been on the rise since 2010 (including 2014)
6. Higher loan amounts have lower borrower APRs
7. California has the highest borrower count
8. There is a strong positive correlation between borrower APR and lender yield
9. 2009 had the lowest borrower count recorded after which there was a stead rise up till 2013
10. 2014 had the lowest borrower count since 2011
11. Borrowers with more investors had access to higher loans
12. Most borrowers have some sort of employment
13. Prosper score has a negative correlation with borrower APR and a positive correlation with original loan amount
14. From 2011 and significantly in the years 2013 and 2014 there was an increase in the number of borrowers seeking loans of hugher amounts (loans above 10,000USD)

## Key Insights for Presentation
1. Distribution of Original loan amount
2. Higher loan amounts have lower borrower APRs
3. Higher income earners access higher loan amounts
4. 2009 had the lowest borrower count recorded after which there was a stead rise up till 2013 followed by 2014 which had the lowest borrower count since 2011
5. California has the highest borrower count

- An overview of the dataset is given
- A simple histogram is used to represent the distribution of the loan amounts.
- A subplot was used to display 
  a.) a scatterplot showing the relationship between loan amounts and lower borrower APRs
  b.) a bar chart showing the relationship between loan amounts and the income range of borrowers
- A bar chart was also used to display the total annual loan amount
- Finally, a bar chart was used to show the states and their borrower counts

