A simple ELT project pulling Airbnb data.

Data was extracted into an S3 Bucket. From here it was transfered into Snowflake. 
DBT was used to clean up and transform the data. Ensuring that the neccessary tests and packages were used for this.

Dashboard was produced using preset highlighting number of hosts, new listings, distribution of super hosts, price distribution and the effects of the full moon.

*Motivation:*

Project was based on an interest in Airbnb listing data and user reviews based on varying obstacles.

It also provided a good opportunity to develop skills and experience in a range of tools. As such, project is more complex than required, utilising dbt, cloud based storagen and visualisation tools.

*Architecture:*

<img width="592" alt="workflow1" src="https://github.com/Usama8H/Airbnb_Listings_Project/assets/147407087/69ffecd4-9757-4872-b0ce-29ac6caab9b6">

1.  Extract data using Reddit API
2.  Load into AWS S3
3.  Copy into Snowflake
4.  Transform using dbt
5.  Create PowerBI or Google Data Studio Dashboard
6.  Orchestrate with Airflow
