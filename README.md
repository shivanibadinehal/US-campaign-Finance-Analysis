# US Campaign Finance Analytics 

## Introduction
The federal government's influence on American political campaigns and elections has steadily increased over the past five decades. Although states primarily administer elections, the federal government plays a significant role in campaign finance regulation. With the US Presidential Election being a critical event impacting both local and global economies, there is a growing need for research on political events' effects on competitive local markets and the global economy. Consequently, various academics and politicians in the US have focused on forecasting election results to inform policy development.

## Abstract
Elections and campaigns are distinct processes governed differently, with the federal government having limited control over political campaigns, except for campaign funding. The main objectives of current election campaigns and policies are voter turnout and electioneering, regulated by federal laws defining permissible and prohibited sources of contributions and expenditures, contribution limits, fundraising prohibitions, permissible uses of campaign funds, and public disclosure of contributions and expenditures.

# Project Goal

The project aims to increase transparency and accountability in the political system by providing insights into campaign finance. It seeks to empower stakeholders with accurate data, analysis, and reporting to make informed decisions and strengthen the democratic process.


## Data Source
The US Campaign Finance Data provided by the Federal Election Commission (FEC) serves as the primary data source for this project. This dataset encompasses information on candidates, committees, political action committees (PACs), campaigns, transactions, contributions, and expenditures related to US elections.

## Data Source - Files Used
- [Data Source - FEC Data Column Names and Abbreviations](https://www.fec.gov/campaign-finance-data/committee-summary-file-description/)

## Data Handling in Financial Analysis
Handling financial data for analysis involves several key steps to ensure accuracy, reliability, and meaningful insights. Here's a breakdown of how financial data is managed in this project:

## Data Import and Cleaning
Importing Data: Financial data files (e.g., .txt and .csv) are imported into a data processing environment like Databricks.
Schema Creation: Custom schemas are created for files without headers to ensure correct data types and formats.
Reading Files: Data files are read using appropriate functions, ensuring all necessary information is loaded correctly.
Data Cleaning: Cleaning processes include handling missing values, removing duplicates, and correcting data types to maintain data integrity.
Data Transformation
Conversion: Data files are converted into more efficient formats (e.g., Parquet) to optimize storage and processing.
Normalization: Data normalization involves restructuring data into a standard format, making it easier to join and analyze across different datasets.
Aggregation: Aggregating data at various levels (e.g., by candidate, state, or transaction type) helps in summarizing large datasets for better insights.

## Data Integration
Merging Dataframes: Relevant dataframes are merged to create comprehensive tables that contain all necessary information for analysis.
Creating Relationships: Establishing relationships between different data tables (e.g., transactions and candidates) allows for more complex queries and deeper analysis.

## Data Validation
Accuracy Checks: Regular checks are performed to ensure data accuracy, such as verifying totals and cross-referencing with original sources.
Consistency Verification: Ensuring that the data remains consistent throughout the analysis process by performing sanity checks and data profiling.

## Data Analysis and Visualization
SQL Queries: SQL is used for querying data to extract specific insights and generate summary tables.
Power Query: Power Query is utilized for data transformation and loading into Excel, enabling seamless integration with other tools.
Tableau Dashboards: Data visualizations are created in Tableau to represent key insights and trends, such as transaction amounts, disbursements, and contributions.

## Statistical and Mathematical Analysis
Essential Statistics: Applying basic statistical measures (mean, median, mode) to understand the distribution of financial data.
Advanced Analytics: Implementing advanced statistical models and machine learning algorithms to predict outcomes and identify patterns in campaign finance.
By systematically handling financial data through these steps, we ensure that the analysis is accurate, reliable, and provides meaningful insights into US campaign finance. This rigorous approach allows financial analysts to make informed decisions and develop strategies based on comprehensive and well-validated data.

# Conclusion

The project successfully transforms raw FEC data into actionable insights, enabling stakeholders to understand campaign expenditures, contributions, and trends. Machine learning models enhance prediction accuracy, facilitating decision-making processes.

# Future Scope

Future research could focus on leveraging emerging technologies like machine learning and natural language processing to automate data analysis and improve campaign finance reporting accuracy and timeliness.

# References
- [Federal Election Commission (FEC)](https://www.fec.gov/)
- [NY Times - Trump-Biden Campaign Donations](https://www.nytimes.com/interactive/2020/10/25/us/politics/trump-biden-campaign-donations.html)
- [Government Accountability Office (GAO) Report](https://www.gao.gov/assets/gao-20-66r.pdf)
- [Congressional Research Service (CRS) Report](https://crsreports.congress.gov/product/pdf/R/R45302)
- [Every CRS Report](https://www.everycrsreport.com/reports/R44318.html)
