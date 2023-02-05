# SanFransisco_HousingMarket

A Jupyter notebook that contains analysis of the housing rental market data for San Francisco. The analysis uses professionally styled and formatted interactive visualizations of the data using hvPlot and GeoViews.

The first part of the project uses numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart. Next I calculated the average prices per square foot, and then again visualized the results as a bar chart.


<img src="Images/housing-units-by-year.png" width="400" height="300">
</p> 

Then I created a new DataFrame named prices_square_foot_by_year by filtering out the “housing_units” column. The new DataFrame includes the averages per year for only the sale price per square foot and the gross rent.

I used hvPlot to plot the prices_square_foot_by_year DataFrame as a line plot.


<img src="Images/avg-sale-px-sq-foot-gross-rent.png" width="400" height="300">
</p> 

Next I compared price per square foot and gross rent and groupedby neighborhoods so as to see the correlation neighborhood to neighborhood. This is displayed as a line plot with a drop down to select each neighborhood. 


<img src="Images/pricing-info-by-neighborhood.png" width="400" height="300">
</p> 

Finally I constructed an interactive points plot of the city that has data points located in each neighborhood to determine where the highest gross rents are and sale price per square foot. 

<img src="Images/interactive_points_plot.png" width="400" height="300">
</p>    