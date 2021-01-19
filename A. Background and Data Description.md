## Background

New York is a big city and gives a lot of opportunities for different kinds of businesses, but learning of the existing market is one of key inputs to plan a successful one. Here I will be building the solution which will help a potential investor or business owner to make the judgment about finding a good spot stop for opening a new place in the city.
More specifically here we will analyze already existing places in New York City and will make a suggestion on the placement of a new Bakery in Manhattan.  
Once having suggested areas, they will be presented on the map for better comprehension.

## Data Description

Following data points are used in this case:
1) The list of New York neighborhoods with respective geographical coordinates;
2) Foursquare’s venues listings with information about places’ coordinates and categories. This will allow to identify the relation of places to neighborhoods and analyze the profile of each neighborhood in terms of what places are typically located there.
3) Foursquare’s categories dictionary which defines the tree-structure of all available place categories on Foursquare. This will allow to apply some grouping over places list to have comparable categories over different neighborhoods. 
4) Geopy to find the NY geographical location for map drawing.