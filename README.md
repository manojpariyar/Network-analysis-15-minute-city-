# Network-analysis-15-minute-city

This is a map showing the road network distance between the houses (points of origin) to different service centres (points of destination) including the shortest paths in a part of municipality. 100 houses are selected randomly for the convenience of data processing. The service centres are Retails, Hospitals, Schools, Kindergartens, Sports Centres, and Churchs. The data on these points of origin and destination are obtained from Open Street Maps Service (https://www.openstreetmap.org/#map=12/67.2781/14.4034) and the Road Network data is obtained from Geonorge (https://www.geonorge.no/). The Road Network consists of 5 types of road, however it is assumed to be able to both walk and bike through for the convenience of this project.

The aim of this project is to find the shortest and the quickest paths from each houses selected to the service centres available and calculate their proximity by walk and by bike. The walk speed and bike speed are assumed to be 5 km per hour and 20 km per hour respectively. The calculated walk time and bike time are attributed to each house points and hence we can see if the service points are within 15 minute walk or bike time from each houses.

The interactive map also includes building polygons and road network with some relevant attributes for reference.

Some basic statistics:

Map:
<img width="558" alt="15 minute city" src="https://github.com/manojpariyar/Network-analysis-15-minute-city-/assets/114010808/936985cb-5c73-493c-a3af-3f7b25969f1b">

## How to use: 
The overall shortest routes can be selected simply by selecting the "Shortest Path" in the selection panel. Since there are 100 houses, the shortest routes also displays 100 routes for each service points. To display the shortest routes for point of origin and point of destination, you can simply select the points on the selection layer. Selecting both points of origin and point of destination at the same time may most likely not display the routes because they may not be connected by shortest routes. Selecting the "Houses" points displays the distance and travel time information. The houses can also be selected based on the scaler display showing the Walk Time (WT) and Bike Time (BT) to different service points.
