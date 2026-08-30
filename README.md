# Airbnb Hotel Booking Analysis

A practical data analysis project using Python to clean and explore Airbnb listing data. The project focuses on pricing, room types, neighbourhoods, hosts, reviews, service fees, and availability.

## About the Project

Raw Airbnb data can contain missing values, duplicate records, inconsistent values, and incorrect data types. In this project, I cleaned and prepared the dataset first and then analysed it to find useful patterns and relationships.

The analysis focuses on:

- Room types and listing distribution
- Listings across neighbourhood groups
- Average prices across neighbourhood groups
- Construction year and price
- Top hosts by listing count
- Host verification and positive reviews
- Price and service fee
- Review rates by location and room type
- Host listing count and availability

## Data Cleaning

Before starting the analysis,

- Checked the dataset structure, columns, and data types
- Checked and handled missing values
- Removed duplicate records
- Cleaned and standardized inconsistent values
- Converted important columns to the correct data types
- Handled invalid price and service fee values
- Filled missing numerical values where appropriate
- Filled missing categorical values with `Unknown`
- Converted date columns to the correct format
- Performed a final data quality check

## Analysis Performed

The cleaned data was used to analyse:

- Room type distribution
- Listings by neighbourhood group
- Average price by neighbourhood group
- Construction year and price relationship
- Top 10 hosts by calculated listing count
- Host verification and positive reviews
- Price and service fee relationship
- Average review rate by neighbourhood group and room type
- Host listing count and availability

## Key Findings

- Manhattan has the highest number of listings.
- Entire home/apt is the most common room type.
- Average prices vary across neighbourhood groups.
- Construction year has a very weak relationship with price.
- Price and service fee have a very strong positive relationship.
- Review rates vary across neighbourhood groups and room types.
- Host listing count has a weak relationship with availability.

## Tools Used

- **Python** - Overall analysis
- **Pandas** - Data cleaning and manipulation
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization
- **Jupyter Notebook** - Analysis and documentation


## Dataset
The original Excel dataset is not included in this repository because of its large file size.

The dataset source and download link are available in [`DATASET.md`](DATASET.md).

