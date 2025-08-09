# Indian-Startup-Funding-Analysis
----------->
This notebook analyzes startup funding data to identify trends, top sectors, top startups, and investment type distribution.

Data Source
The data used in this analysis is from the "startup_funding.csv" file.

Analysis Steps
Data Loading and Initial Inspection: The notebook loads the data into a pandas DataFrame and displays the head and information about the DataFrame to understand its structure and content.

Data Cleaning and Preparation:

The 'Date dd/mm/yyyy' column is converted to datetime objects.
The 'Amount in USD' column is cleaned by removing commas and converting it to numeric type.
Funding Trend Analysis: The total funding amount is calculated and displayed over time, aggregated by month.

Top Sectors Analysis: The top 5 industry verticals based on the number of startups are identified and displayed.

Top Startups Analysis: The top 5 startups based on the number of funding rounds are identified and displayed.

Investment Type Distribution: The distribution of different investment types is calculated and displayed.

Visualization: The notebook generates several plots to visualize the findings:

Startup Funding Trend Over Time (Line plot)
Top 5 Industry Verticals by Count (Bar plot)
Top 5 Cities by Funding Amount (Bar plot)
Top 5 Startups by Funding Amount (Bar plot)
Distribution of Investment Types (Bar plot)
Visualizations
The visualizations provide insights into:

How startup funding has changed over time.
Which industry verticals have the most startups.
Which cities receive the most funding.
Which startups have received the most funding rounds.
The prevalence of different investment types.


https://colab.research.google.com/drive/18dfHOfJsN5m8Em8qhuUc6cWXoxXp45mL#scrollTo=yX4C_UdEbA03
