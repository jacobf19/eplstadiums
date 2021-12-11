# [Premier League Stadiums](https://jacobf19.github.io/eplstadiums/)
This repository hosts the data for the GEOG 495 final project, which is a map of English Premier League stadiums.

## Webpage Features
[Premier League Stadiums](https://jacobf19.github.io/eplstadiums/)
![Webpage](https://github.com/jacobf19/eplstadiums/blob/main/images/fullwebpage.png)

The main function of this webpage is to display the locations of the English Premier League stadiums, across the country of England, within the United Kingdom. 

On the left side of the page, the title describes what is shown on the map, this season's Premier League stadiums. Underneath, information about each Premier League team is listed by team in alphabetical order. The team name in blue is followed by the stadium name in red, which then shows the city, the stadium capacity, and the year the stadium opened. The user can scroll on this list to see all 20 stadiums. 

![Sidebar](https://github.com/jacobf19/eplstadiums/blob/main/images/fullsidebar.png)

The main part of the webpage is a map of the 20 Premier League stadiums in England. This map can be zoomed in and out by scrolling, as well as navigation by dragging, to view locations in England and around the world. 

There is a search bar on the top left of the map, which allows the user to search locations in England. When a location is searched, the map will change extent to display the location as well as the closest Premier League Stadium. The side panel will organize by distance to the searched point, and a new entry will appear under each team in the panel showing the distance from the stadium to the point. 

![Search](https://github.com/jacobf19/eplstadiums/blob/main/images/stadiumsearch.png)

## Map Features
The default web map is set to display the entire country of England with all 20 stadiums in view. The stadium locations are represented by the Premier League logo, which is a circular purple lion with a crown. These stadiums are set against a custom basemap.

This map was made using ***Mapbox GL JS*** and is hosted on ***GitHub***.

### Basemap
This basemap was created using [Mapbox Studio Style Editor](https://studio.mapbox.com/styles/jacobf19/ckwigbmr25a4c14rx05emxggb/edit/#11.71/51.5063/-0.0888), which allows the user to create a custom basemap. The default monochrome basemap was edited in this style editor in order to display the stadiums in a way which clearly showed the locations of the stadium without other distractions. 

At default extent, major highways are displayed in light yellow. After zooming into a specific city, railroads and transit lines are displayed in dark grey. Further zooming into a specific city reveals metro train system stations, stark black and grey icons which are set against the white basemap and yellow highways. The major UK highway system and the railway lines across the country are specifically chosen for the purpose of supporter travel between grounds. The EPL, and English football in general, has a strong culture of supporters traveling to other team's stadiums for "Away Days" to support their team in other cities. Many fans drive, but some also take rail, therefore the inclusion of both has been made to show how stadiums are connected to commuter networks and how a fan might travel between stadiums. 

Upon further zoom, the footprints of buildings are set in grey on top of the white basemap. Labels for major cities are shown at the default extent, with more minor cities, neighborhoods, and even building titles at smaller extents. 

### Stadium Pop-Ups
When a stadium is selected through a click or a search, a pop-up will appear on the map with the stadium name and the team name. This pop up will disappear upon any other click on the map. These stadium pop-ups are particularly helpful when looking at cities like London, Manchester, or Liverpool, which have multiple teams located within the city. 

![Pop-Up](https://github.com/jacobf19/eplstadiums/blob/main/images/search.png)

## Uses
This map which displays the locations of Premier League stadiums has multiple potential uses.

First, the map can be used to understand the distance from one stadium to another or to any other location within England. For a new fan of the sport, this could help in making a decision for which team to support, simply by distance. Likewise, for someone traveling to England, a trip to a Premier League game may be a fascinating and exciting experience. With either of these uses, a list of distances to stadiums from a particular location allows for an easy decision of which stadium to visit or which team to support. The information on the side panel allows for a user to select a stadium with desirable characteristics as well.

At the most basic level, a Premier League fan or anyone with an interest in learning UK geography may enjoy seeing the locations of Premier League stadiums across the entire country, or even within a specific city like London with six Premier League stadiums. 

![London](https://github.com/jacobf19/eplstadiums/blob/main/images/london.png)

## Data Sources
Location data for the stadiums was compiled by searching for coordinates in [Google Maps](https://www.google.com/maps)

Stadium and team specific pages can be found on the [Premier League website](https://www.premierleague.com/)

Mapbox Data: [Custom Mapbox Style](https://studio.mapbox.com/styles/jacobf19/ckwigbmr25a4c14rx05emxggb/edit/#11.71/51.5063/-0.0888)

Icon: [Premier League Logo](https://www.premierleague.com/)

Logos: [Arsenal](https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FArsenal_F.C.&psig=AOvVaw1keO_6Oqn72VZL48_i9Sxo&ust=1639175827929000&source=images&cd=vfe&ved=0CAwQjhxqFwoTCOjS8Prj1_QCFQAAAAAdAAAAABAF)


## Acknowledgements
This project is based off of a tutorial by Mapbox to [Build a Store Locator](https://docs.mapbox.com/help/tutorials/building-a-store-locator/)

