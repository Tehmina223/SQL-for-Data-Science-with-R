# SQL-for-Data-Science-with-R

Project Title: Analyzing Canadian Crop Production for Investment Decisions
Objective:
This project involves analyzing historical crop production data in Canada to provide insights for a US Venture Capital firm that is considering investments in the microbrewery and microdistillery industry. The analysis focuses on assessing the supply and price volatility of key crops, with an emphasis on understanding the impact of the relative value of the Canadian and US dollars.

Tools & Technologies Used:

R: Data manipulation and analysis.
RSQLite: Database management and SQL queries.
Datasets:
Canadian Principal Crops (1908-2020)
Farm Product Prices (1980-2020)
Bank of Canada Daily Average Exchange Rates (USD/CAD)
Project Tasks:

Database Creation:

Established a connection to an SQLite database.
Created four tables (CROP_DATA, FARM_PRICES, DAILY_FX, MONTHLY_FX) and populated them with data from the provided datasets.
Data Analysis via SQL Queries:

Counted records in the farm prices dataset.
Identified geographies included in the farm prices dataset.
Determined hectares of Rye harvested in Canada in 1968.
Queried the farm prices table for Rye.
Identified provinces that grew Barley.
Found the first and last dates for farm prices data.
Identified crops with farm prices ≥ $350 per metric tonne.
Ranked crop types in Saskatchewan by average yield in 2000.
Ranked crops and geographies by average yield since 2000.
Calculated wheat harvests in Canada in the most recent year.
Used a join to calculate the monthly price per metric tonne of Canola in Saskatchewan in both CAD and USD.
Outcome:
The project successfully provided a macro-view of Canada's crop farming industry, delivering insights into crop performance and price volatility. This analysis aids in strategic investment decisions for the firm's supply chain in the craft beer and spirits markets.

