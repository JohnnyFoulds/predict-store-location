# Predict Store Location

A pet store chain is selecting the location for its next store. Use data preparation techniques to build a robust analytic dataset and 
use it to build a predictive model to select the best location for a new store.

## Problem Definition

> Describe that the goal is to find a location and mention that this project is very superficial with a limited amount of data and more 
advanced techniques and more features (such as spacial data from OpenStreetMap, social media data (Foursquare), etc. will be used.

# Data Sources

- **p2-2010-pawdacity-monthly-sales.csv** - 2010 Monthly sales data for Pawdacity stores.
	* Name
	* Address
	* City
	* State
	* Zip
	* January - December sales columns
- **p2-partially-parsed-wy-web-scrape.csv** - Web scraped census data for WY.
	* City
	* County
	* 2014 Estimate
	* 2010 Census
	* 2000 Census
- **p2-wy-453910-naics-data.csv** - Sales data for competing stores for WY obtained from the US Census Bureau (https://www.naics.com/naics-code-description/?code=453910).
	* Business Name
	* Physical City Name
	* Sales Volume
	* CASS_LastLine
- **p2-wy-demographic-data** - Demographic data for WY.
	* City
	* County
	* Land Area
	* Households with Under 18
	* Population Density
	* Total Families

## Feature Selection

- City
- State
- Country
- Pawdacity Annual Sales
- Competitor Annual Average Sales
- Competitor Annual Total Sales
- 2014 Estimate
- 2010 Census
- 2000 Census
- Land Area
- Households with Under 18
- Population Density
- Total Families

## Data Preparation

- Missing Data
- Data Inconsistencies
- Unnecessary Attributes

## Data Set Summary

## Outliers

# Web References

## EDA
- https://towardsdatascience.com/exploratory-data-analysis-in-python-c9a77dfa39ce
- https://app.pluralsight.com/course-player?clipId=3b2fb8f0-49e9-4165-bd68-fbfdb8c5cb6b - df.corr(method='pearson'))

## IQR
- What Is the Interquartile Range Rule? - https://www.thoughtco.com/what-is-the-interquartile-range-rule-3126244
- Interquartile Ranges & Outliers - https://www.purplemath.com/modules/boxwhisk3.htm

## Predict Best Branch Locations For a Company
- https://datascience.stackexchange.com/questions/43602/predict-best-branch-locations-for-a-company
- https://www.jla-data.net/eng/branch-network-optimization-in-r/
- https://www.thebalancesmb.com/choosing-a-retail-store-location-2890245
- https://blog.spatial.ai/how-to-predict-the-best-neighborhood-for-a-retailer-within-any-market
- https://blog.spatial.ai/the-essential-guide-to-geosocial-data
- https://www.idealspot.com/tag/site-selection/
- https://www.linkedin.com/pulse/what-factors-should-ecommerce-based-business-when-brick-eisenberg/
- https://www.idealspot.com/how-to-choose-the-ideal-retail-or-restaurant-location-2/
- https://www.thinkwithgoogle.com/marketing-resources/micro-moments/why-consumer-intent-more-powerful-than-demographics/
- https://towardsdatascience.com/walking-through-a-linear-regression-dca9942111e4
- https://www.researchgate.net/publication/335447956_Intelligent_site_selection_for_bricks-and-mortar_stores