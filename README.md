# Hospital-Price-Transparancy

<h2>Hospital Pricing: an Exploration of the Cost of Common Proceedures</h2>
Due to the newly-enacted price transparancy rule, hospitals are now required to disclose the amounts they charge for the services and proceedures they render, making this data available for analysis. The chargemaster data from this project can be found on the [California Health and Human Services webpage] (https://data.chhs.ca.gov/dataset/chargemasters).

1. Extract and consolidate chargemaster data from of 261 California hospitals.
2. Convert the data to sqlite format and query it from a SQL database.
3. Use SQLAlchemy to query the data with Python to facilitate further analysis.
4. Generate summary statistics and data visualizations to tell a cohesive story about the nature of hospital pricing in California, with an emphasis on the price breakdown in terms of types of services rendered and price discrpencies between locations.
<p></p>
<h3>The Files</h3>

|+--convert_files.ipynb -> converts all xls files to xlsx format to facilitate systematic data extraction
|+--1095_collection.ipynb -> Extracts 1045 AB form data from each hospital's workbook, first identifying relevant sheets by keyword then organizing and extracting this data.

<p></p>
<h2>Results</h2>
After analysis is complete, all models, visualizations, and breakdowns of their substantive meaning will be displayed here.