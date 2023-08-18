# San Francisco Housing

## 1. Calculated and Plotted the Housing Units per Year
#### This section calculates the average number of housing units per year and visualizes the results using a bar chart.
<img width="789" alt="Housing_Units_by_Year" src="https://github.com/dxmolnar/san_francisco_housing/assets/127795314/306c1419-12b3-4c8e-8774-e33983e584b2">

## 2. Calculated and Plotted the Average Sale Prices per Square Foot
#### This section calculated the average sale price per square foot by year, filtered out the housing_units column, and visualized the results using an interactive line plot.
<img width="781" alt="Avg_Sale_Price_per_sqft" src="https://github.com/dxmolnar/san_francisco_housing/assets/127795314/ea1c7c42-cded-4260-9da2-e1b020f36e41">

### 3. Compared the Average Sale Prices by Neighborhood

#### In this section, the data is grouped by year and neighborhood, and the mean values are calculated. An interactive line plot is created using `hvplot`, allowing users to select a neighborhood from a dropdown menu and view the average price per square foot for the selected neighborhood.
<img width="834" alt="Sale_Price_per_Neighborhood_Anza_Vista" src="https://github.com/dxmolnar/san_francisco_housing/assets/127795314/0de134c9-48c6-43cd-b16b-a3b542de03b5">

## 4. Built an Interactive Neighborhood Map

#### In this section I built an interactive map that combines the neighborhood location data with the average prices to create an interactive map using `hvplot` and `Folium`. The map displays points for each neighborhood, with the size of the points representing the sale price per square foot and the color representing the gross rent.
<img width="817" alt="Folium_plot" src="https://github.com/dxmolnar/san_francisco_housing/assets/127795314/e5d51022-a81e-4e44-bd25-6dd77cee7570">

## Libraries Used
1. Python
2. Pandas
3. Hvplot
4. Holoviews
5. Pathlib
6. Numpy
7. Mathplotlib
8. Folium
