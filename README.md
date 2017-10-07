# housing-demand
future housing demand projection

# Objective

The goal of this analysis is to project future housing demand in Texas with focus on Houston metropolitan area

# Data
 * Time period:
 * Monthly level
 * Metropolitan Statistical Area (MSA) level: Based on the multi-county area specified by The Office of Management & Budget in 2013
   * Houston-The Woodlands-Sugar Land, TX
   * Dallas-Fort Worth-Arlington, TX
   * San Antonio-New Braunfels, TX

# Methodology:
  * Quantify housing demand: existing home sales 
  * Variables: 
    * dependent variable: 

# Analysis
  * descriptive statistics analysis is conducted to assess the overall housing KPI metrics in 3 selected MSA
  * a RF model is built to project future housing demand

# Directory

* raw_data directory contains all the raw data resources used in this analysis:
  * `sales.xlsx`: monthly MSA level of Sales, Dollar Volume, Average Listing Price, Median Listing Price, Total Listings,	Months Inventory (1990 - 2017)
    * source:   Real Estate Center, Texas A&M University, [website](https://www.recenter.tamu.edu/data/housing-activity/)
  * `dataPermit_full.csv`: monthly MSA level of Building permit data for single-family, 2-4 family and 5-plus family units (1980 - 2017)
    * source:  U.S. Bureau of Census and Real Estate Center at Texas A&M University, [website](https://www.recenter.tamu.edu/data/building-permits/)
  * `dataEmpl_full.csv`: monthly MSA level of Employment and unemployment data (1990 - 2017)
    * source:  U.S. Bureau of Labor Statistics and Real Estate Center at Texas A&M University, [website](https://www.recenter.tamu.edu/data/employment/)
  * `dataPop_full.csv`: annual MSA level of Population estimates and demographic components of change (births, deaths and migration) (1970 - 2016)
    * source:  U.S. Bureau of Census and Real Estate Center at Texas A&M University,[website](https://www.recenter.tamu.edu/data/population/)
  * `household_inc.xls`: annual state level of Median Household Income (1984 - 2016)
    * source: U.S. Bureau of Census, [webiste](https://www.census.gov/topics/income-poverty/income/data/tables.All.html)
  * `wage-growth-data.xlsx`: monthly region level of wage growth rate (1997 - 2017)
    * source: Current Population Survey, Bureau of Labor Statistics, and Federal Reserve Bank of Atlanta Calculations, [website](https://www.frbatlanta.org/chcs/wage-growth-tracker.aspx?panel=1)
  * `libor.csv`: daily level of LIBRO(1986 - 2017)
    * source: Federal Reserve Bank
  * `wti_oil.csv`: monthly level of oil price(1980 - 2017)
    * source: Federal Reserve Bank
  * `Metro_MedianRentalPrice_AllHomes.csv`: monthly metro level of Median price of homes listed for rent on Zillow for All homes (single-family, condominium and co-operative homes)(2010 - 2017)
    * source: Zillow Real Estate Research, [webstie](https://www.zillow.com/research/data/)

* _modeling_data_ directory contains the integretated and cleaned dataset for analysis and modeling

* _code_ directory contains the python code used for analysis and modeling

* _presentation_ directory contains the jupyter notebook used for presentation


    
    
