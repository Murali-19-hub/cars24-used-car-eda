# Cars24 Used Car Market Analysis
### Web Scraping & Exploratory Data Analysis

## Project Overview

This project focuses on collecting and analyzing used car listing data from Cars24 using Python web scraping techniques and Exploratory Data Analysis (EDA). The objective is to understand used car pricing patterns, examine factors influencing resale value, and identify trends across brands, vehicle age, fuel types, transmission types, and cities.

## Project Objectives

- Extract used car listing information from Cars24.
- Clean and transform raw data for analysis.
- Analyze resale prices across car brands and cities.
- Explore the relationship between vehicle age, kilometers driven, and resale price.
- Compare pricing patterns across fuel and transmission types.
- Identify market trends and derive actionable business insights.

## Tools & Technologies

- **Python** — Programming and data analysis
- **Requests** — Retrieving webpage content
- **BeautifulSoup** — HTML parsing and data extraction
- **Regular Expressions** — Extracting structured information
- **Pandas & NumPy** — Data cleaning and manipulation
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Development and analysis

## Project Workflow

### 1. Web Scraping
- Selected Cars24 as the target platform.
- Generated listing URLs using selected cities and car brands.
- Retrieved webpage content using HTTP requests and appropriate headers.
- Parsed HTML content to extract relevant used car listing information.

### 2. Data Cleaning & Preparation
- Inspected dataset structure, data types, missing values, and duplicates.
- Cleaned and converted relevant fields into appropriate formats.
- Prepared numerical and categorical variables for analysis.
- Created additional features to support price and vehicle-age comparisons.

### 3. Exploratory Data Analysis
- Analyzed distributions of car brands, prices, fuel types, transmission types, and vehicle age.
- Compared average resale prices across brands and cities.
- Examined the relationship between resale prices, vehicle age, and kilometers driven.
- Compared prices across fuel types and transmission categories.
- Used statistical summaries and visualizations to identify patterns and relationships.

### 4. Insights & Interpretation
- Evaluated the distribution of used car listings across price segments.
- Identified differences in average resale prices across brands.
- Examined how vehicle age and usage relate to resale value.
- Compared market patterns across cities and vehicle categories.

## Key Findings

- Budget-priced vehicles account for a substantial share of the analyzed listings.
- BMW has the highest average resale price among the brands analyzed.
- Resale prices generally decrease as vehicle age and kilometers driven increase.
- Automatic vehicles have a higher average listed price than manual vehicles in the collected dataset.
- Petrol vehicles account for the largest share of the analyzed listings.
- New Delhi and Noida are among the leading cities by listing volume in the analysis.

*These findings reflect the collected dataset and may not represent the entire used car market.*

## Business Value

The analysis provides a data-driven view of used car pricing and listing patterns. It can help buyers compare vehicle prices, help dealerships explore inventory distribution, and support preliminary assessments of resale-value trends across brands and vehicle categories.

## Disclaimer

This project is intended for educational and analytical purposes. Data collection should comply with Cars24's applicable terms of service, access restrictions, and relevant laws. Results are based on the listings collected during the project.

## Author

**Murali Krishna Reddy**
