# Tata-Group-Data-Visualisation

This project involves cleaning and analyzing an online retail dataset to provide actionable insights through interactive Tableau visualizations. Below is a summary of the steps performed:

### Data Cleaning
Handling Invalid Entries:

Filtered out rows where Quantity < 1 to exclude invalid returns or incorrect values.
Removed rows with Unit Price < 0 to ensure only valid transactions were included.
Preparation:

Data cleaning was performed directly in Tableau, using filters in the Data Source Tab and calculated fields for dynamic condition-based exclusions.

### Visualizations
Each visualization was created on a separate Tableau worksheet to address specific business questions:

1. Time Series of Revenue (2011)
Filtered the data to include only transactions from the year 2011.
Created a calculated field for Revenue ([Quantity] * [Unit Price]).
Generated a monthly time series using a line chart to show trends in revenue.
This visualization helps the CEO analyze seasonal trends for forecasting.
2. Top 10 Countries by Revenue (Excluding UK)
Filtered out the United Kingdom from the data.
Created a bar chart to display the top 10 countries ranked by total revenue.
Added Quantity as a secondary metric for comparison with revenue.
Provides insights into high-performing countries for strategic marketing decisions.
Top 10 Customers by Revenue
Identified the top 10 customers based on their revenue contribution.
Sorted the data in descending order, starting with the highest revenue-generating customer.
Created a bar chart to highlight key customers for targeted engagement and retention strategies.
4. Product Demand by Region (Excluding UK)
Filtered out the United Kingdom to focus on international expansion opportunities.
Used a Tableau Map visualization to display product demand (Quantity) across all other countries.
Highlighted regions with the greatest demand for strategic expansion planning.
