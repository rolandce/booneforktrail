#Boone Fork Trail Project Description

For this project, I wanted to depict a trail on the Blue Ridge Parkway that I had completed. I embarked on this 5.2 mile hike last summer, allowing me to obtain a better understanding of the route and markers. Using multiple libraries and data sources, I feel that I compiled a pleasing web map.

#Major Functions
- My Route Function: This function added the route and markers to the map.


- Revised My Route Function: This function allowed me to style the line representing my route and markers on the Boone Fork Trail. Using the L.geoJson(), I was able to seperate the trail and the markers into different objects within my script by filtering the data based on geometry type. The LineString command for the trail data could then be customized by color, weight, opacity, and dashArray.

- My Stops Function: This function allowed me to style my points (markers) on the trail. This was included in the string of code listed above in the revised My Route Function. It split up the lines and points by geometry type. 

- onEachFeature Function: This was used for the markers. This allowed the user to retreieve specific information about these features by mousing over the markers. This took information from the originally dowloaded geojson.io file (which was then transferred to a .js file) and placed the 'name' property on display.

#Libraries and Data Sources
Trail Route: [Google Maps](https://www.google.com/maps/dir/Julian+Price+Memorial+Park,+Blue+Ridge+Parkway,+Blowing+Rock,+NC/Julian+Price+Campground,+Blue+Rdg+Pkwy,+Blowing+Rock,+NC+28605/@36.1406207,-81.7581704,13.91z/data=!4m19!4m18!1m10!1m1!1s0x8850ee238054bc65:0x62b5754799e12fb4!2m2!1d-81.737895!2d36.1367743!3m4!1m2!1d-81.7370893!2d36.1545623!3s0x8850f1d7c63a3f81:0xcdd9a69c0cfc8612!1m5!1m1!1s0x8850ee32b9bddcbf:0xdcb4dedd47aec5b2!2m2!1d-81.736107!2d36.1391883!3e2?entry=ttu)
Transformation from Google Maps to GPX: [Maps to GPX](https://mapstogpx.com/)
Transformation from GPX to Geojson: [Geojson.io](http://geojson.io/#map=13.11/36.14763/-81.73621)
Leaflet Basemap: [Esri_NatGeoWorldMap](https://leaflet-extras.github.io/leaflet-providers/preview/#filter=Esri.NatGeoWorldMap)
Trail Information: [All Trails: Boone Fork Trail](https://www.alltrails.com/trail/us/north-carolina/boone-fork-trail--8)