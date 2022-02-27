# Final Project

## Content

The topic we have selected was to examine crime rate data and housing price data by county and create a machine learning tool to see if we could create an environment that would predict housing price based on the level of crime that occurs in a given county.

The topic was selected out of a mutual interest in finances, crime/crime rate data, and how it may affect the housing market and where people choose to live.


## Communication Tools Used

* Files were shared using a GitHub repository whith separate branches for each member being used. Commits and pushes to the main branch are done upon request.
* Day-to-day text communication was done using the Slack communication platform.
* Group meetings are held over Zoom meetings on webcam to share ideas and to work more intricately on the project.


## Datasets

* [Zillow House Price Data](https://www.kaggle.com/paultimothymooney/zillow-house-price-data): <Sale_Prices_City.csv>
  * The dataset contains the median price at which all home types across various cities were sold on Zillow website each month from 2008 to 2020. 

* Crime in Context, 1975-2015: <crime.csv> from https://www.kaggle.com/marshallproject/crime-rates
  * The dataset contains crime data from 68 police jurisdictions with populations of 250,000 or greater from 1975 to 2015. 

* United States Cities Database: <uscities.csv> from https://simplemaps.com/data/us-cities
  * The dataset contains the mapping between US cities and counties.

* MEDIAN INCOME IN THE PAST 12 MONTHS: <medium_income_2011-2015.csv> from https://data.census.gov/cedsci
  * The dataset contains the median household income for each US county from 2011 to 2015.

We will only use the data from all these datasets from the period of 2011 to 2015. Since we are not able to retrive the median household income for each city, we will alter the original csv file <Sale_Prices_City.csv> by mapping each city to its county using the United States Cities Database <uscities.csv> in Excel. Also in order to reduce the file sizes of the median income datasets from US Census, unnecessary columns are droppped using Excel.



## Machine Learning Module



## Analysis Implementation

What we are looking for in are data set is a correlation between crime and housing princes in counties across the United States. To complement this data, we will be using median income data to display how income is associated with housing prices and crime in these counties.

Using the data we will try to display how housing prices have changed within a given year as a result of the crime in these cities, also taking into account the change in median income.

Currently based on the crime dataset we have what is listed are types of crimes, population, county, and year.
The other dataset will have a median household dataset that will be used in conjunction with the crime dataset.

If we were running a real-estate site we could use this data to determine which state and town are good for future investment. From an investment standpoint, I would use this data to purchase homes at a time when housing prices are down because of crime. Usually, this is when large investments are made in real estate. 
