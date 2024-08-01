# Car-Resale-Data-Analysis-Project
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)   ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)     <img src="https://img.shields.io/badge/databricks-%23FF3621.svg?&style=for-the-badge&logo=databricks&logoColor=white" />
 ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black)    

Aim:

The aim of this project is to conduct a comprehensive analysis of car resale trends and factors influencing resale prices in the Indian market. Leveraging a dataset sourced from Kaggle, encompassing resale car information from the year 2023, this project demonstrates proficiency in utilizing AWS S3, Databricks, and PySpark for data ingestion, cleaning, transformation, and visualization. By meticulously examining the dataset, the project seeks to unravel insights into the dynamics of the Indian car resale market, shedding light on key determinants shaping resale prices.

Tools Used:

1) AWS S3 (External Storage System): Utilized for secure and scalable storage of the dataset.
2) Databricks: Employed for data ingestion, cleaning, transformation, and visualization tasks.
3) PySpark (Programming Language): For creating ETL data pipeline and data cleaning.
4) SQL: For performing data analysis on Transformed data.

Dataset:

Link: Car Resale Prices Dataset

Records: 17446

Columns: 15


Process Diagram:


![Process Diagram](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/a43f6ebc-0a50-456a-a7fb-37813497195f)



Procedure:

The project follows a systematic approach to draw conclusions in a chronological order:

1) Dataset Upload to AWS S3: The raw dataset is uploaded from the local machine to an AWS S3 bucket, ensuring secure and scalable storage.

2) Data Ingestion with Databricks: Utilizing Databricks, the raw dataset stored in AWS S3 is ingested for further processing and analysis.

3) Data Cleaning and Transformation: This crucial stage involves several key steps:
    - Dropping unnecessary columns.
    - Removing duplicate entries.
    - Transforming various columns (renaming, changing data formats, altering column values, modifying data types, creating new columns).
    - Handling null values through imputation or removal.
    - Exporting the cleaned dataset back to AWS S3 for storage and creating a table for facilitating advanced SQL queries.
    - Generating a statistical summary of the cleaned dataset.
   
4) Data Analysis and Visualization:
   
   - Conduct thorough data analysis to uncover trends and patterns.
   - Utilize visualization techniques to present insights effectively.

Key Questions to Address:

1) Identifying the market share of various car manufacturers in the resale market.
2) Unveiling the most popular car models from the leading car manufacturers.
3) Analyzing how the resale market varies across different registration years.
4) Investigating how ownership type influences car resale trends.
5) Understanding consumer preferences regarding insurance types for used car purchases.
6) Examining the geographical distribution of car resale activities across cities in India.

Visaulizations:

1) Which car companies dominated the car re-sale market in 2023?
   

![car resale per car company](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/dcb4b016-16c6-4ad3-bf68-7b9e14f0fe3a)


2) Which top 5 car models of top 3 companies dominated the re-sale market?


![Top 5 car models per company](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/87ce1871-2fce-4624-aca7-589cb219663a)


3) Car Resale Trends Based on Registration Years.


![car sold per registration year](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/79494649-7922-4d2b-bdcd-d55979f88447)


4) Car Resale Trend Based on Ownership Type in India.


![car sold per ownership type](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/e2249736-16bc-499d-8206-e6a466629c1b)


5) Analyze Insurance Type Preferences for Used Car Purchases.


![car sold per insuarance type](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/b294bf9a-298a-4fb3-8264-c733662f0e62)


6) Analysis of Car Resale Distribution Across Cities.


 ![car sold per city](https://github.com/Jay-05022000/Car-Resale-Data-Analysis-Project/assets/110780565/77025fc1-9436-4242-9553-7929b7f1ce52)


Conclusion:

By addressing these key questions, the project provides valuable insights into the dynamics of the Indian car resale market, facilitating informed decision-making for stakeholders in the automotive industry.
