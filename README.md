# Should I Stay or Should I Go
*Helping you decide which city you should go to next.*

This project was created by Shelley Obery and Robert Bozsik as the final project for the Ironhack Data Analytics Bootcamp. It is an ongoing project to develop a dataset of EU cities, which can be used in a comparison program that implements KMeans clustering.

# Task:
The goal is to demonstrate the skills the students have built throughout the bootcamp, which includes: data analytics, cleaning, restructuring, visualisations and statistics.

# Project details:
We created a city clustering system, that groups the capital cities of Europe into 4 clusters based on features chosen by the user. These are weather- and/or socio-economic features, such as number of sunny hours per season, the safety index of a city, among others.

# Features:
### Weather
 - summer sun hours, summer high temperatures, summer precipitation days
 - spring sun hours, spring high temperatures, spring precipitation days
 - winter sun hours, winter high temperatures, winter precipitation days
 - autumn sun hours, autumn high temperatures, autumn precipitation days
 - climate
 
### Socio-economic Indices
 - cost_of_living
 - health_care
 - pollution
 - property_income_ratio
 - purchasing_power
 - safety
 - traffic_time
 - quality_of_life
 
# Folders
- archived: contains notebooks that are no longer used for the finished product.
- data: a collection of the data we are using.
- new_features: notebooks containing functions/improvements that are still under construction.
- notebooks: all notebooks used for the current city clustering tool.

# Notebooks
- 1_City_recommender_MVP.ipynb: this book contains the prototype of our function.
- 2_EDA_initial_analysis.ipynb: here you can find analysis of the data and preparation for usage.
- 3_Manual_additions.ipynb: contains manual additions to the capital city dataset, which could not be obtained through web-scraping.
- 4_Scraping_climatedata.ipynb: code for scraping data from climatedata.eu.
- 5_Scraping_numbeo.ipynb: code for scraping data from Numbeo.
- 6_Merging_all_data.ipynb: combining all data.


# Project presentation:
https://docs.google.com/presentation/d/1WNTZ1GRcsgc9r4Hti8-8F0tT5bt_O0hJty1h0DEKn0o/edit?usp=sharing

# Resources:
Raw data:
 - weather data: https://www.climatedata.eu/
 - socio-economic data: https://www.numbeo.com/cost-of-living/
 - latitudes and longitudes of cities: http://techslides.com/list-of-countries-and-capitals

Analysis idea:
 - https://medium.com/analytics-vidhya/city-recommender-system-with-python-part-3-3-deployment-finding-my-schitts-creek-2019971e2c4d
 
# Tech stack:
Python: https://www.python.org/ \
Pandas: https://pandas.pydata.org/ \
NumPy: https://numpy.org/ \
Matplotlib: https://matplotlib.org/ \
Seaborn: http://seaborn.pydata.org/ \
Folium (displaying the cities on a map): https://python-visualization.github.io/folium/ \
scikit-learn (clustering the cities): https://scikit-learn.org/stable/ \
Jupyter Notebook: https://jupyter.org/

# Example:
![health care index example](/images/health_care_index_example.png)
