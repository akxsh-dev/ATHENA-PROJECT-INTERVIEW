# Craigslist-Vehicle-Listings

I established an Azure Data Lake Storage (ADLS) account, creating two distinct Gen2 containers—one dedicated to storing raw data and the other for the transformed dataset. After registering the application and obtaining the access keys, I seamlessly mounted ADLS to Databricks.

Within a dedicated Databricks resource group, I configured an Apache Spark cluster to facilitate data processing. Setting up authentication configuration with the acquired keys, I effectively mounted the raw data from ADLS to a Python notebook.

In the notebook, I meticulously transformed the data schema to align with the required data types. Once the transformation was complete, I mounted the newly processed data back into the ADLS container and created a duplicate of the transformed dataset to continue our analysis. This streamlined approach ensured efficient data handling and analysis within the project.

I conducted an in-depth analysis utilizing SQL to extract valuable insights from the dataset. This analysis encompassed several key aspects, including:

1. Regional Car Listings: I identified and categorized car listings by their respective regions, along with brand and model names, vehicle types, and transmission types.

2. Regional Car Brands: The analysis highlighted the prevalence of car brands in different regions.

3. Regional Car Brands and Total Counts: I determined the total count of cars associated with each regional car brand, providing a comprehensive view of brand popularity.

4. Regional Availability by Condition: The dataset was examined to assess the availability of cars in various conditions across regions.

5. Ready-to-Sell Cars with No Damage: A specific focus was placed on identifying ready-to-sell cars that exhibited no signs of damage.

This comprehensive analysis provided actionable insights into the regional car market, assisting in strategic decision-making and potentially uncovering opportunities for optimization and growth.

Skills: Azure Databricks · Azure Data Lake · Apache Spark · Python (Programming Language)
