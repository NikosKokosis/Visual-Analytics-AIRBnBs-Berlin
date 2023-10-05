# Berlin Airbnb Insights

## Sections
- **[Project Overview](#project-overview)**
- **[Data Source](#data-source)**
- **[Project Highlights](#project-highlights)**
- **[Project Structure](#project-structure)**
- **[Conclusions](#conclusions)**
- **[Dependencies](#dependencies)**

## Project Overview

Welcome to the Berlin Airbnb Insights project! In this project, we explore the dynamic world of Berlin's Airbnb market, using data analysis and visualization techniques to uncover valuable insights. We delve into various aspects of Berlin's Airbnb landscape, including pricing trends, room types, host analysis, and geographical distribution.

## Data Source

- **Dataset**: [Berlin Airbnb Listings](http://insideairbnb.com/get-the-data/)
- **Dataset Details**: [Dataset Details](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=1322284596)

## Project Highlights

Here's a glimpse of what we've explored in this project:

- **Comparison of Price and Room Type by Last Review Date**: We start by analyzing the prices of Airbnb accommodations in Berlin from October 2019 to March 2023. We categorize accommodations into four types and provide insights into how pricing evolves over time.

- **Distribution of Room Types**: We calculate the number of different room types and their proportions, shedding light on the variety of accommodations available in Berlin.

- **Relationship Between Host Type and Listing Availability Days**: We examine the correlation between listing availability and host type. This includes analyzing how SuperHost and Not SuperHost categories differ in terms of availability.

- **Host Statistics**: We create a new DataFrame to obtain statistics about hosts, including a "total_rate" column that combines all host ratings. We then identify the best hosts based on their ratings.

- **Price Comparison of Numa and Nena**: We explore the future pricing trends of Numa and Nena, two Airbnb providers. This comparison reveals variations in pricing dynamics between the two companies.

- **Price Distribution**: We visualize the distribution of prices for both companies, highlighting differences in pricing strategies.

- **Geospatial Analysis**: Using the Folium library, we create map visualizations to explore the geographical distribution of Airbnb listings in Berlin, focusing on specific hosts with the best ratings and reviews.

- **Neighborhood Price Analysis**: We analyze the distribution of Airbnb listings in different neighborhoods and identify pricing variations among neighborhood groups in Berlin.

## Project Structure

The project is structured into several sections, with each section corresponding to the project highlights mentioned above. The code and insights for each section can be found in a single [Jupyter Notebook](Berlin_Code/Visual_Analytics_AIRBnBs_Berlin.ipynb).

## Conclusions

Our project provides valuable insights into Berlin's Airbnb market, including pricing trends, host performance, and geographic distribution. These insights can be used by travelers to make informed choices and by hosts to optimize their listings.

## Dependencies

This project uses Python libraries for data analysis, visualization, and mapping. Ensure you have the required libraries installed as mentioned in the project notebook.