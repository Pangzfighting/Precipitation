# Precipitation
## Section 1: Data Cleaning
#### The primary objective of this section is to transform a grid-level dataset into a district-level dataset for five Indian states: Gujarat, Kerala, Pondicherry, Punjab, and Rajasthan. The process involves matching each grid point to its corresponding district based on a weighted average of daily mean temperature, daily mean rainfall, and daily total rainfall. The weights are determined by the inverse of the squared distance from each district's geographic center.

### Steps:
#### Utilize geodist or vincenty commands to calculate the distance between each grid point and every district centroid.
#### Apply the weighted average algorithm to obtain district-level daily datasets for the years 2009-2013.

## Section 2: Data Exploration
#### This section utilizes the district-level daily dataset from Section 1 for data exploration, focusing on documenting the monsoon season in various districts.

### Steps:
#### For the Jaipur district in Rajasthan, create a time series dataset of daily rainfall averaged over the five years.
#### Generate a scatterplot of rainfall by day using the time series data. Identify the start and end dates of the monsoon season in Jaipur.
#### Format graphs to meet publication standards and save them as .pdf files.
#### Create publication-quality tables depicting annual average temperature by state and year.

