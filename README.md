# DS785-Capstone

File 1: Census Data.ipynb - This script pulled total, male, and female population data for all NYC ZIP codes from the U.S. Census API, covering the years 2019 to 2022. The data is later merged with existing ZIP-level income information for analysis. You’ll need a Census API key to run the code. 

File 2: Data Cleaning.ipynb - This script processed a large NYC 311 Service Requests CSV file using Dask for scalable cleaning and Pandas for final merging. Reads the raw 311 dataset using Dask for efficient handling of large data. Dropped rows missing critical fields like ZIP code, complaint type, coordinates, etc. Saved the cleaned data as chunked CSV files in a specified directory. Find and merged all cleaned CSV chunks using Pandas into a single csv file for analysis.

File 3: Analysis.ipynb - Changed the date format, rename few columns and saved the cleaned file as 311_cleaned_final.csv. Ran all Exploratory analysis in this file.

File 4. Models.ipynb - Ran all the models on the dataset
