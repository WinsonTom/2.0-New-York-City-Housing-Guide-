# NYC Housing Guide 2.0

**NYC Housing 2.0 - Final Tableau Dashboard: https://public.tableau.com/shared/2PB4H57BQ?:display_count=n&:origin=viz_share_link**
**Youtube Video explaining Dashboard: https://youtu.be/CpnRrUZJtOY?si=XHDLLInriJNQXc-W**


Revisions from the original project. https://github.com/WinsonTom/New-York-City-Housing-Guide

How is this different from my original project in : https://public.tableau.com/app/profile/winson.tom/viz/NewYorkCityHousingGuideFinal/Story1

In my original I was emphasizing how location is the primary factor determining pricing. I gave per zip code pricing, differences in pricing per neighborhood & per property type, price ranges for the addresses, price per square foot, and neighborhood safety rating. While this was good to explore the data that was already provided, I found this perspective to be for “data collectors” rather than a functional tool for actual buyers. People who would use the previous dashboard would include developers, people working for the Census, or writers looking for a broader point of view. However, this was intended to **serve buyers wanting to move into New York City** . With that you need a lot more granular image. It requires answering more day to day living, personal questions. This dashboard and 2nd round of the project looks to solve the problem of “I don’t know anything about the different parts of NYC and what it’s like to live there. Give me a summary “. 

Specific problem this project answers:
**“I want to buy a personal residence in NYC, but I don’t know anything about NYC neighborhoods. What property is right for me?” - Buyers**

Instructions:

- Click into Scripts & Data.
- ***Click the README*** . Readme details the start point, data analysis steps taken , and ending results.

Contents:  
- 1.0 demonstrates how the data was cleaned from its original state to its revised state
- 2.0 adds the perceptions of the neighborhood and then combining it into the primary data set.
- 3.0 goes through two transformations to group zipcodes and neighborhoods. Then using the neighborhoods to identify safety ratings.
- 4.0 uses the longitude and latitude to find the distance from Midtown.
- 5.0 continues to revise neighborhoods by narrowing down neighborhoods, then identifying the population, the square miles, and therefore the population density.
- 6.0 creates relevant visualizations through Python.
- 7.0 is the final deliverable the client should receive. 

## Python Usage:
	- Loading Large Datasets
	- Dropping Duplicates
	- Removing unnecessary columns
	- Renaming columns
	- Condensing information within columns
	- Splitting column information
	- Identifying data types
	- Calculating counts of variables
	- Add in neighborhood column for further identification
	- Check for null values
	- Check for missing values
	- Remove null values
 	- Identify outliers
	- Correct outliers/incorrect information
	- Creating separate Data-frames
	- Identify correlations
	- Create visuals, Heat Maps, Scatter plots, histograms, folium maps
	- Loading GeoJson Files
	- Create folium map
	- Prepare data for regression analysis
	- Create test set
	- Regression analysis
	- Identify slope, mean squared error, R2 score
	- Create training set
	- Plot training set
	- Plot elbow curve
	- Create clusters
	- Aggregate cluster data
	- Load Quandl data
	- Time Series Analysis to identify decomposition 
	- Add in Flag - Neighborhood safety rating
	- Fill values with Niche.com data 
	- Add pricing range column
	- Export finalized cleaned wrangled data

## Excel Usage:
- Sorting & Filtering data
- Individual revisions when errors are identified
- Finding Medians of each Borough's population density
- Distance between two points, longitude + latitude calculations
- Population Density

## Tableau Usage:
- Connecting raw data 
- Creating sheets using measures and dimensions
- Appropriate use of filters
- Differentiating through use of colors
- Various use of visuals
- Creating Dashboards
- Storytelling
- Optimizing home buyer's search process on tangible variables impacting daily life
