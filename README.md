##VICTORIA SAMUEL_ DATA ANALYST PORTFOLIO 

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

# LITA-DATA-ANALYSIS-DOCUMENTATION

### International Breweries Data Exploration Analysis

**Goal:** 
To examine the profits for each country and also profit for each geopolitical zone
To know the country with the highest profits and the btand that brought in more profit


**Description:** The dataset contains records of brands sold, countries and plant_cost, cost, region, months, year, profit and unit_cost records by country between 2017-2019. This project includes the following steps: data loading, data cleaning and preprocessing and EDA (exploratory data analysis).

### Data Sources
The primary source data used here is a CSV data file to and this an open source data from sites such as KAGGLEor FRED or any other repository site.

**Technology:** SQL Server

### Tools Used
- Microsoft Excel [Download here](https://www.microsoft.com)
     1. for Data cleaning
     2. visualization
- SQL- Structured Querry Language for data querrying
- Github- for portfolio Building

**Skills:** data analysis, data visualization, 


### Codes used
 1. select * from[International Breweries eccel]
    
 2. select SUM (profit) as Totalprofit from [International Breweries eccel]
where countries = 'Nigeria'and years ='2019'

3. select SUM (profit) as Totalprofit from [International Breweries eccel]

4. select SUM (profit) as Totalprofit from [International Breweries eccel]
where countries = 'senegal'

5. select brands, SUM(profit) as totalprofit
from [International Breweries eccel]
where countries = 'Nigeria'and YEARS = '2017'
Group by Brands 
order by 2 desc

6. Group by Brands 
order by 2 desc

7. SELECT countries,
  CASE
 WHEN COUNTRIES IN ('Nigeria','Ghana') then 'ANGLOPHONE'
	ELSE 'FRANCOPHONE'
END as CountriesGroup,
sum (profit) as Totalprofit from [international breweries eccel]
where years in ('2017', '2018', '2019')
Group by Countries

### Data Cleaning and Preparations
The initail phase of data cleaning and preparations,we perform the following action;
1.Dta loading and inspection
2. Handling missing variables
3. Data cleaningand formatting

### Exploratoratory Data Analysis
EDA involved the exploring of the Data to answer some questions about the Data such as:
 - What is the overall sales trend
 - Which product are top sellers
 - What are the products on peak sales
   
