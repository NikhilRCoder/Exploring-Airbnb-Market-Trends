# Exploring-Airbnb-Market-Trends
Bangkok City has a variety of Airbnb listings to meet the high demand for temporary lodging for travelers, with several different price levels, room types, and locations.  Importing, cleaning data, data manipulation and report insights.



## Data Sources

- **listings.csv:** Summary information and metrics for listings in Bangkok.
- **reviews.csv:** Summary review data and listing ID.
- **calendar.csv.gz:** Detailed calendar data.
- **reviews.csv.gz:** Detailed review data.
- **neighbourhoods.csv:** Neighbourhood list for geo filtering.
- **neighbourhoods.geojson:** GeoJSON file of neighbourhoods of the city.

## Analysis Overview

### Questions Explored:

1. **Distribution of Airbnb Prices in Bangkok**
2. **Average Prices by Neighborhood Group**
3. **Relationship Between Room Type and Price**
4. **Correlation Between Number of Reviews and Price**
5. **Monthly Trends in Reviews**

### Steps and Findings:

1. **Distribution of Airbnb Prices in Bangkok**
   - Visualized using a histogram to show the frequency of different price ranges.
   - Insight: Most listings are priced within a certain range, with some high-priced outliers.

2. **Average Prices by Neighborhood Group**
   - Calculated and visualized average prices for each neighborhood group using a bar plot.
   - Insight: Certain neighborhoods have significantly higher average prices compared to others.

3. **Relationship Between Room Type and Price**
   - Analyzed using a box plot to show the price distribution for different room types.
   - Insight: Room types exhibit varying price ranges, with entire homes/apartments typically costing more.

4. **Correlation Between Number of Reviews and Price**
   - Visualized using a scatter plot with a regression line to identify trends.
   - Insight: The number of reviews generally correlates with the price, indicating popularity and value.

5. **Monthly Trends in Reviews**
   - Analyzed the number of reviews per month using a line plot.
   - Insight: Reviews show seasonal patterns, indicating trends in tourist visits.

## How to Run the Analysis

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Airbnb_Bangkok_Analysis.git
   cd Airbnb_Bangkok_Analysis
