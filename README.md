# Renewable Electricity Data Analysis
This repository contains a dataset about global renewable electricity production as well as a jupyter notebook for map-based data visualization using Python Folium and the two html maps that were created using the python code in the notebook.

The maps represent the percentage of renewable electricity in total electricity production by country on a world map using a simple color scheme.

The dataset: Renewable_elec_production_percentage.xlsx  
The jupyter notebook: Renewable Electricity Production by Country.ipynb  
Simple map for 2017: choropleth_2017.html  
Map with timeslider for 1990 - 2017: choropleth_timeslider_1990_2017.html  

## Requirements 
The notebook is written in Python 3.8. The additional packages that are required to run the notebook are the following:
- jupyter => 1.0.0
- pandas => 1.2.4
- numpy => 1.20.2
- openpyxl => 3.0.7
- folium => 0.12.1
- geopandas => 0.9.0

## Running the notebook
From the root folder of the repository, simply execute ```jupyter notebook``` in your terminal, open the jupyter link in your browser and open the notebook that will appear in the list of files in jupyter. The notebook is self-explanatory and includes some background information on the topic of renewable electricity. 

## Time spent 
In total, I spent approximately 20 hours on this project, including the time spent on finding a topic and dataset, cleansing the data, learning about folium and geopandas library, implementing the maps and commenting the notebook and creating this repository. 

Most of the time I spent on implementing the maps and troubleshooting, however, data cleansing also took me a little bit of time, because adapting the country names between the electricity dataset and the country geometries was time consuming.  
The second map (with the time slider) took me much more time than the first map, which was pretty straight-forward. 

## Resources
The dataset comes from: https://unstats.un.org/unsd/envstats/qindicators.cshtml

For implementing the two maps, I have manly relied on a blogpost for the first map: https://vverde.github.io/blob/interactivechoropleth.html ; and the example notebook for the TimeSliderChoropleth plugin for the second map: https://nbviewer.jupyter.org/github/python-visualization/folium/blob/master/examples/TimeSliderChoropleth.ipynb
