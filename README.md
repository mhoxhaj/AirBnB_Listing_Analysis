# AirBnB_Listing_Analysis
This project focuses on analyzing AirBnB listings in Paris to understand the impact of recent regulations on the rental market. 
The goal is to clean, prepare, and visualize the data, focusing on trends related to price, accommodations, and host activity over time. 
Key tasks include data profiling, quality assurance, and visualization to uncover insights on how regulations affect the number of new hosts and price levels.

Objectives
## Objective 1: Profile & QA the Data
a. Connect to the Listings.csv file: Import the AirBnB data from the provided Listings.csv file.
b. Clean and prepare data: Convert any date columns (e.g., host_since) into datetime format to ensure proper analysis.
c. Filter for Paris listings: Filter the data to include only rows where the city is Paris, and keep only the columns host_since, neighbourhood, city, accommodates, and price.
d. QA the Paris listings data:
Check for missing values in the relevant columns (host_since, neighbourhood, accommodates, and price).
Calculate basic statistics (minimum, maximum, and average) for the numeric columns accommodates and price.
## Objective 2: Prepare the Data for Visualization
a. Group by neighbourhood: Create a table named paris_listings_neighbourhood that groups listings by neighbourhood. 
Calculate the mean price for each neighbourhood and sort the results from low to high.
b. Analyze most expensive neighbourhood:
Filter the data to focus on the most expensive neighbourhood in Paris.
Group by the accommodates column and calculate the mean price for each group (sorted low to high). 
This will create a table named paris_listings_accommodations.
c. Analyze listings over time: Create a table named paris_listings_over_time by grouping the listings by host_since year. 
Calculate the average price and count of listings (representing the number of new hosts per year).
## Objective 3: Visualize the Data
a. Bar chart of average price by neighbourhood: Create a horizontal bar chart to show the average price by neighbourhood in Paris. 
Ensure that the chart has a clear title, with appropriately labeled axes.
b. Bar chart of average price by accommodates: Create a horizontal bar chart showing the average price by accommodates in the most expensive neighbourhood. 
Add a title and adjust the axes labels accordingly.
c. Line charts for new hosts and average price over time:
Create two separate line charts: one for the count of new hosts over time, and another showing the average price over time.
Set the y-axis limit to start at 0, and ensure that both charts have clear titles and labeled axes.
## Dual-Axis Line Chart
a. Combine new hosts and average price over time. 
