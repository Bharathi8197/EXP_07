**Exp 7 :  Build Cartographic Visualization for Multiple Datasets Involving Various Countries of the World; States and Districts in India**

**AIM:**
To build cartographic visualizations (map-based visuals) for datasets involving global and Indian geographical entities (countries, states, and districts) using Python libraries such as folium and geopandas.

**EQUIPMENTS REQUIRED:**
 Python
 Libraries: pandas, folium, geopandas, json
 World GeoJSON File: For country boundaries
  URL: https://raw.githubusercontent.com/python-visualization/folium/master/examples/data/world-countries.json
 World Population Data: For population statistics by country
  URL: https://raw.githubusercontent.com/plotly/datasets/master/2014_world_gdp_with_codes.csv

**ALGORITHM:**
1)Import necessary Python libraries.
2)Load the GeoJSON file for world boundaries.
3)Load a dataset containing information like GDP or population by country.
4)Merge the geographical and statistical data.
5)Use folium.Choropleth() to create a shaded map based on statistical values (e.g., GDP or population).
6)Save the final map as an interactive HTML file.

**PROGRAM:**


   






**EXPECTED OUTPUT:**
**Note**: Upload your output screenshots as follows
    An interactive choropleth map is generated.
    Each country is shaded based on its GDP value.
    The map includes a legend showing GDP ranges.
    Users can zoom, pan, and hover to explore the data geographically.

**RESULT:**
This experiment demonstrates how to build a cartographic visualization that combines geographical boundary data with statistical information (GDP) to produce a rich, interactive, and informative map.
