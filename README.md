# Airbnb Hotel Booking Analysis

A Python-based data analysis project focused on cleaning Airbnb listing data and finding useful patterns in pricing, room types, neighbourhoods, hosts, reviews, service fees, and availability.

## Project Overview

This project uses an Airbnb hotel booking dataset to:

- Clean and prepare the data for analysis
- Understand different room types and neighbourhoods
- Compare listing prices across neighbourhood groups
- Study the relationship between construction year and price
- Identify the top hosts by listing count
- Compare verified and unverified hosts based on positive reviews
- Analyse the relationship between price and service fee
- Compare review ratings across neighbourhood groups and room types
- Study the relationship between host listing count and availability

## Data Cleaning

The dataset was prepared before analysis by:

- Checking data types and missing values
- Removing duplicate records
- Cleaning column names
- Converting important columns to numeric format
- Handling invalid negative prices and service fees
- Filling missing numerical values using the median
- Filling missing categorical values with `Unknown`
- Performing a final data quality check

## Key Analysis

The project covers:

1. Room type distribution
2. Listing distribution by neighbourhood group
3. Average price by neighbourhood group
4. Construction year vs. price
5. Top 10 hosts by calculated listing count
6. Host verification vs. positive reviews
7. Price vs. service fee
8. Review rate by neighbourhood group and room type
9. Host listing count vs. availability

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel dataset

## Project Structure

```text
Airbnb-Hotel-Booking-Analysis/
│
├── Airbnb_Hotel_Booking_Analysis.ipynb
├── README.md
├── requirements.txt
└── images/
```

## How to Run

1. Clone or download this repository.
2. Open `Airbnb_Hotel_Booking_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Install the required Python libraries.
4. Run the notebook cells in order.

## Key Findings

- Manhattan has the highest number of listings.
- Entire home/apt is the most common room type.
- Average prices vary across neighbourhood groups.
- Construction year has a very weak relationship with price.
- Price and service fee show a very strong positive relationship.
- Review rates vary across neighbourhood groups and room types.
- Host listing count has a weak relationship with availability.

## Author

**Mohit Patidar**

Data Analytics Project
