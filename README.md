# leaflet-challenge
This task required visualizing an earthquake dataset obtained from the USGS GeoJSON Feed page using leaflet. I selected "All Earthquakes from the Past 7 Days". With the URL of this JSON, I imported the data using Leaflet to create a map of theearthquakes that occured in the last seven days over a map of the world. The map plots all earthquakes based on their longitude and latitude, with data markers reflecting earthquake magnitude through size and depth through color intensity. Higher magnitude earthquakes appear larger, while earthquakes with greater depth are darker in color. Additionally, popups provide extra information when markers are clicked. There is a legend included to provide context for the color scheme of the map data.

I used leaflet documentation, found at https://leafletjs.com/reference.html, to find examples of the pointtolayer, style, and oneachfeature code. The scale of depth goes from -10 to 90+ changing color from green to red creating the following map. 

![image](https://github.com/kelseajade/leaflet-challenge/assets/152021966/75299ccc-232e-47dd-9ff6-165dd5a51652)
