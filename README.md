# Capstone-2-Data-Analysis-of-Transjakarta-Dataset
A Capstone Project for module 2 (DTI-DS Purwadhika School). This repository showcasing data cleaning, processing, and analysis of Transjakarta Datasets.
## Importing Library and Dataset
First, All libraries need to be imported. The libraries are pandas, seaborn, matplotlib, numpy, and geopandas. Then the pandas is used to read the .csv files of the Transjakarta Dataset. To understand the data more clearly, the top 10 data is pulled using the '''.head() command'''
## Data Cleaning
For Data Cleaning, Checking for duplicate values and null values is conducted. Dataset info also checked in order to check whether the data is in the correct format. Author also tried to detect and correct the data manually here, until decided to use mapping fill the null values automatically, and drop the null value that cannot be filled using the mapping.
## Processing and Analysis
For Analysis, Adding region column to identify in which part of Jakarta is the stops located. The region column using the latitude and longitude that provided in the dataset, matched with the latitude and longitude of the region boundaries, obtained from the BPS Indonesia as the data source. Some Graphic also made to identify the busiest hour each day of week, most corridor used, and Busiest stop. For further analysis, tableau is utilized.
The cleaned data is saved in a new .csv file.
## Contribution
Please feel free to open a pull request, sent to my email ariqulfikri@gmail.com or submit an issue if you have suggestions or encountered any problem.
