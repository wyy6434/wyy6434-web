3D game with Mapbox SDK

### Screenshot of Unity Panels
<div align=center><img width="500" height="500" src="https://github.com/wyy6434/wyy6434-web/blob/master/wyy6434-web/3DGame/Screen_Shot.png">

![alt text][logo]
[logo]: https://github.com/wyy6434/wyy6434-web/blob/master/wyy6434-web/3DGame/Screen_Shot.png
      
### Screenshot of C# Script
![alt text][logo]

[logo]: https://github.com/wyy6434/wyy6434-web/blob/master/interactive_map/map.png "map"


### Reflective Analysis      
This map is deiginated for urban planners and educators who interested in promoting the cultures of Victoria, British Columbia. The distribution of Art and culture facilities, to some extent, reflect cultural policy and the community planning, therefore, the main goal of this map is to examine the progress of cultural policy and community planning in order to boost the development of arts, culture and entertainment activities. Currently, urban core reamains the primary centre for the arts and culture in the Capital region. However, peripheral regions are not beneficial from these facilities, more community plannings are needed.

This map is using schools (yellow circle) as reference points to see how many facilities (red circle) are located within 2km buffer. Since the arts are accessible to a broad diversity of people and groups, and highly correlated with education, so choosing schools as reference points is a better choice. The 2 km radius of buffer is randomly chosen. If mouse hover over any circle popup box school name or facility name would popup. Unfortunately, this interactive map is a way below my expectation, there are a lot of room for improvement in this map. Firstly, if there is a highlight effect when clicking a school point, it would have a better visualization. Secondly, buffers are shown at once and overlaying each other affect the visualization badly. It could be improved if we click a school point each time and appear its highlighted buffer zone. Thirdly, it is better to have a result box below the map that shows how many art and cultural facilities fall within buffer zone.

I found two websites that are helpful for the future improvement.
1. This website shows highlighted single polygon when clicked, this may apply to my highlighted single buffer zone. (https://leafletjs.com/examples/choropleth/)
2. This websire shows how highlight marker. (https://github.com/brandonxiang/leaflet.marker.highlight)

### URL Link
https://wyy6434.github.io/wyy6434-web/interactive_map/interactive_map_1.html
