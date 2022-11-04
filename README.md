# Proptech_San_Francisco
Use data visualization skills, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.
## Import Required Libraries and dependencies
- [ ] import pandas as pd
- [ ] import hvplot.pandas
- [ ] from pathlib import Path
## Read in the data
 Using read_csv function and Path module, create a data frame. Csv file sfo_neighborhoods_census_data.csv
 Use the head and tail functions to view first and last 5 rows.
# Caluclate and Plot the Housing Units per Year
- using groupby function to group the data by year.
- using hvplot function plot the housing_units_by_year.
- Style and Format your plot to ensure professionally styled visualization.
# Calculate and Plot the Average Sale prices per square foot.
- group the data by year, then average the results. 
- create a new dataFrame named prices_square_foot_by_year by filtering out the housing_units column. The new Dataframe should include the averages prices per year for only the sale price per square foot.
- use hvplot to plot the prices_square_foot_by_year DataFrame as a line plot.
- Style the plot.
# Compare the Average sale price by neighborhood.
- create new dataframe by year and neighborhood, aggregate the results by the mean of the groups.
- filter out the housing_units column to create a DataFrame that includes only the sale_price_sqr_foot and gross_rent averages per year.
- use hvplot to visualize the sale_price_sqr_foot and gross_rent. use the groupby parameter to create an interactive widget!
