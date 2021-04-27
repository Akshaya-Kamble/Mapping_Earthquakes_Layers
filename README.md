# Mapping_Earthquakes
Mapping earthquake data


### Overview of the Project
In this project we have created the eathquake map with three different layers as street , satellite and dark.All these three layers are mutually exclusive. The map further plots three kinds of data,the location of earthquakes is marked with a circle that has a radius and color depending on the magnitude of the earthquake.The major earthquakes with magnitude greater than 4.5 are marked with a bigger radius and the tectonic plates are shown with the red lines. All this data can be selected together or viewed as required. The map also shows a legend for the magnitude on the right corner.The circle markers when clicked also show the magnitude and location.

### Result

#### 1. Adding the tectonic plate data
Using JavaScript, Leaflet.js, and geoJSON data, we can add the tectonic plate data using d3.json(), add the data using the geoJSON() layer, The tectonic plate LineString data is set to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.
![](https://github.com/Akshaya-Kamble/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Reference%20Images/tectonic%20plates.PNG)

#### 2. Adding the major earthquake data
Using JavaScript, Leaflet.js, and geoJSON data, we can add major earthquake data to the map using d3.json(), and a color and set the radius of the circle based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().
![](https://github.com/Akshaya-Kamble/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Reference%20Images/major%20earthquakes.PNG)

#### 3. Adding a third map style
Using JavaScript and Leaflet.js we add a third map style which is dark to your earthquake map.
![](https://github.com/Akshaya-Kamble/Mapping_Earthquakes/blob/main/Earthquake_Challenge/Reference%20Images/satellite.PNG)

### Conclusion
The map can be zoomed and toggled between the three different layers as street , satellite and dark to show real time earthquake data.The other options like earthquake locations,tectonic plates and major earthquakes can also be selected as required.
