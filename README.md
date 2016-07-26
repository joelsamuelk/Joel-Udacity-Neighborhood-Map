# Joel-Udacity-Neighborhood-Map

## Overview 
This application is single page application featuring a map of my neighborhood Cape Town and all the universities and colleges around.

## Download
Use github link (https://github.com/joelsamuelk/Joel-Udacity-Neighborhood-Map) to download or clone the repository.

## Instalation 
Run the index.html file found in the directory 

## Map 
The Map is built using the Google Map API (http://maps.googleapis.com/maps/api/js?key=AIzaSyDSCcy2htnsbh9edXydftA1ESGTP-ZU2Zo&libraries=places&callback=googleSuccess) 
and pulls through the foursqure API (https://api.foursquare.com/v2/venues/search?client_id=VGW53IWWPVNRZBDUNHFW1Z2GQZBHFYIDWOTNA5M2S2AIXFVL&client_secret=URVFRTKS0AWCICYJBGEPFWUHYAU3CTB0SPKCBCVHDB3FG4LL&v=20150321) for all the Map location details displayed 

The Google Map API has been issued using my work responsive email: joel@responsive.co.za which enables the ability to get hold of the Google Map details.

To accomplish this project, you must start by defining your initial coordinates which loads the map and finds all the locations within the 100.000 radius.
In my case, I have used my beautiful City Cape Town and managed to load all universities and college around the city with the coordinates below            

 //Cape Town Coordinates to load map
 CapeTown = new google.maps.LatLng(-33.9248685, 18.4240553),

The Map uses a custom loading gif before all locations have been displayed and also it uses svg marker and a cusytom style to match my choosen map theme using the color #02b3e4

## Contributors
The Udacity Team and my responsive (goresponsive.com) colleagues