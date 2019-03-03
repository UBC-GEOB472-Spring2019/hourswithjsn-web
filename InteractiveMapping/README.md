# An Interactive Map of Correctional Facilities in BC

## Reflective Analysis

![](InteractiveMapping/CorrectionalFacilities.JPG)

I designed an interactive map for correctional facilities in British Columbia, the intended user for this map is anyone who may be concerned
and want to find out where the correctional facilities are located in BC as well as where different types of correctional facilities are located.
Overall, I believe my map was successful in showing all the locations of these facilities on the leaflet map, and map users are able to type in
the facility types to differentiate their search results. However, there were definitely improvements to be made in my map. For instance, I understand
my search bar looks for specific combinations of words to match my feature collection type which in this case was the correctional facility types,
so one of the problems I encountered was youth custody. Since youth custody within my GeoJSON file was written in one word, users had to input "youthcustody"
in order for the facilities to be highlighted. Also, I would want to integrate more user information in my map, for example, when users hover over the 
facilities, I would want it to give more information such as exact location or the placename. 

The design of the map uses a highlight all function as well as a search function, the two functions both featured a user button to press with the latter with
an extra search bar to find different facility types. I believe using these two interactivity adds understanding for users. Comparing to presenting a map
showing all facilities, users may want to know more information that are available in the JSON file such as address, name, facility types, hours of operation, etc.
Therefore, having a search bar and being able to provide the tool to highlight different facility types offer users more information to access.
Moreover, in terms of my cartographic styling in relation to the chocie of my data, I wanted to choose a basemap that is simple and does not contain any
geographical features. Therefore, I selected a basemap which only concerns with city names and major road networks since I am presenting information about
correctional facilities.

## Improvements to be made

As mentioned previously, I want my map to be more user friendly in terms of searching for information about the different facilities. I would want to 
improve upon the coding aspect which can be more intelligent in recognizing words with the example of "youthcustody". I also wanted to improve the level
of information it can provide, for example, providing the facility's name and address. Also I would want to explore and incorporate some of the Turf
functions that could be integrated into my map such as identifying distance between facilities.

[Link to the full map](https://editor.p5js.org/hourswithjsn/present/o04bU5qVD)
