# Lab 1: Web Mapping
### Screenshot
![alt text][logo]

[logo]: https://github.com/wyy6434/wyy6434-web/blob/master/web_mapping_graffiti/Capture1.PNG "map"

### Reflective Analysis
This heat map is designated for sociologists who want to do some research on the linkage between graffiti and social issues in different neighbourhoods. The map consists of two layers: graffiti and neighbourhood boundary. For the graffiti layer, I chose to present as a heat map instead a cluster of discrete points because it is a visual aid than an accurate way to show point density that answers how data is distributed. The colour schemes of this heat map is sequential that areas with the most point features are presented as red, and as yellow when areas had least point features. 

The map focusing on City of Vancouver, so I set the initial zoom view and minimum zoom level of the map into 11.5. Since the labels of streets are considered as “noise” at the initial view, which affecting users’ experience (the map would look messy if street labels are visible at initial view), so I decided to set street labels invisible and labels of city and neighbourhoods are visible in the initial view. As users zoom in, the street labels appear out.

This heat map helps sociologists to discover which neighbourhood has the most or the least graffitis. The overall visual effect that I am seeking is to turn the heat map into a interactive map that when users zoom in, they can click to the points and there is a popup box. Users can see what type of graffiti does the point presents (inserting photos), some information and stories about the graffitis, as well as the artist. Unfortunately, at this stage it is hard to accomplish as more advanced coding needed. 

### URL Link
https://api.mapbox.com/styles/v1/wyy6434/cjrtu08at01oq1fppbt4t5ve2.html?fresh=true&title=true&access_token=pk.eyJ1Ijoid3l5NjQzNCIsImEiOiJjanJ1NGphM3cwNHhpNDlsNXJqbDVsbGpyIn0.WsnRUtOwWc6L46WwA-EPZw#11.6/49.245074/-123.119609/360

### Map Critique
Few points need to improve:
1. Few neighbourhood names did not appear at the initial view (e.g Dunbar).
2. The position of neighbourhood labels should locate at the centre of the polygon.
3. It would be better if study area (city of Vancouver) stands out.
4. Interactivity needed: when map users click on the neighbourhood polygon the total number of graffiti appears within the popup box.
