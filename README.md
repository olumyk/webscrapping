
# GTA Real Estate Price Analysis through Web Scraping

## Overview

This project aims to understand real estate price variations in the Greater Toronto Area (GTA) by leveraging web scraping techniques to collect and analyze data from the [Zolo.ca](https://zolo.ca) website. The analysis identifies affordable and expensive areas within the GTA based on the scraped data.

## Project Structure

- `WebScrapingCode.ipynb`: Contains all the code for scraping, cleaning, and analyzing the data.
- `scraped_data.csv`: The raw data file consisting of over 6,000 listings scraped from Zolo.ca.
- `clean_data.csv`: The cleaned dataset with derived features for analysis.
- `.pptx`: A slide presentation summarizing the insights from the analysis.

## Data Collection

### Scraped Data Features

The scraped data includes the following features:
- HouseWeb
- Address
- Price
- PropertyType
- Bedroom
- BedroomPlus
- Bathroom
- SquareFootage
- Style
- Age
- Community
- DatePosted

### Cleaned Data Features

The cleaned dataset consists of these features:
- HouseWeb
- Address
- Price
- PropertyType
- Bedroom
- BedroomPlus
- Bathroom
- SquareFootage
- Style
- DatePosted
- BuildingAge
- City
- Region
- HouseAddress
- Lat_Long

## Technologies Used

- **Python**: Core programming language for the project.
- **BeautifulSoup**: For parsing HTML and extracting data.
- **Selenium**: For web browser automation and dynamic content scraping.
- **Pandas**: For data manipulation and cleaning.


## Insights

- **Affordable Areas**: Based on average house prices, affordable areas within the GTA have been identified. These areas include Georgina Island, Brock, Oshawa, and others.
- **Expensive Areas**: The analysis also highlights the most expensive areas, located outside the core of Toronto, such as Stouffville, Mississauga, Markham, Mono, and King.
- **Visualization**: Charts and visualizations provide a clear view of price variations across different regions in the GTA.

## Conclusion

By scraping over 6,000 house listings and analyzing the data, this project provides valuable insights into real estate price trends in the GTA. The findings can help potential homebuyers make informed decisions about where to purchase property based on affordability.

