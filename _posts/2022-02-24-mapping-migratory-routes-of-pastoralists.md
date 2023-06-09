---
layout: post
title:  "Mapping migratory routes of pastoralists across India"
excerpt: "We worked with Center for Pastoralism recently to illustrate a few migratory routes in different states that pastoralists usually travel through."
categories: [ Mapping ]
author: janastu
featured: true
image: https://i.imgur.com/5OxlwFb.png
toc: false
comments: true
---

# Mapping migratory routes of pastoralists across India 


We worked with Center for Pastoralism recently to illustrate a few migratory routes in different states that pastoralists usually travel through. This was for a pandemic-state-of-the-nation report. The data was from a few different states like Gujarat, Uttarakhand, Jammu and Kashmir, Karnataka, Andhra Pradesh, Telangana, Tamil Nadu and Leh. It was a diverse set of information for eg. We were collating information from multiple sources, some were from CfP, which were research papers that needs to be parsed into tabular data and some from Gopi's research travels.

1. The Tamil Nadu set had information about breeders of different species of cattle, where their home base was, where they went for pastures seasonally etc.
2. The Gujarat Set had specific and detailed information of different migratory communities and the cyclical routes they take through north and south Gujarat
3. The Dakkhani set collected by Gopi related to monsoon pattern and flood based pastures selection by the shepherds.
4. Summer and winter pasture migration was also the focus of Himachal Pradesh, J&K and Leh

### Workflow

The whole activity was done in phases, First going through the documents, and 
1. Place Names Identification (Team)
2. Reverse geolocation search, place name to Lat Long mapping (Team)
3. Review of the places and latlong (Team and CfP)
4. Import data to Mapbox (Micah) or Google My Maps (Bhanu and Athithya) to plot the points on the map, and see if manual intervention is required to correct some points
6. Prepare a URL 
7. Yatharth illustrates using Figma by adding the generated map as a layer to trace on
8. Adding Map tileset to the illustrated map, using mapbox.
9. Getting feeback from CfP and iterate




### Data Structure
The data was structured in different sheets for different migratory paths and had information about which communities used these different paths. The excel sheet had names of places in a route, the communities travelling in the path and a route number for each path. The names of the places were uniquely identified and geolocated, speculating about proximity to the last geolocated place in the route(many times there were multiple places with the same name. The latitude and longitude after the geolocation was identified with a google maps url so that the team could independantly verify it.
    
We used many different ways to identify places
* Manually scrolling through the map along the places already identified 
* Checking altenate names of places
* Assuming directionality through topography
* Checking both Google and OSM to cross-verify
* Google sheets plugin which does reverse geo names query using OSM

This is how the final sheet would look.

![This is how the final sheet would look.](https://i.imgur.com/JsgnXGY.png)

Since on the excel sheet there were only the names of places when we first received them, we would often have some deviations. These deviations could be a forking route, or a multiple origin route, or a place that appears on multiple routes. Sometimes an indicated place was a region, that we couldn't often pinpoint, so we would have to see what made the most sense for the rest of the route.

This map here with question (?) mark and orange circles have been annotated and shared between Micah and Yatharth to denote doubts and names of places that don't appear.
![](https://i.imgur.com/JzUgGH8.jpg)

The Tamil Nadu map was about cattle breeds, their home bases and the migratory paths they take seasonally. Gujarat, Himachal, Dakkhani region and JK were about the paths of specific communities
![Tamil Nadu Route Sheet](https://i.imgur.com/cIUcTna.png)




### Story of the Deccan sheep
Gopi Krishna of Mitan Handicrafts was consulted for migratory routes in Deccan. Since, he has his network of people in this region with whom he has already worked, and some routes he has already documented for various kinds of significance. In one session we sat out, and started reading out names of places around Anantapur has starting point of the migration route branching out north towards bellary, South until tumkur and vellore, West towards Davangere and until Shimoga, North Western Belgaum shepherds moving towards South East and back.
The Deccan shepherds are very much dependent of the South Western (SW) and North Eastern (NE) monsoon and flooding patterns, and keep the herds away from flooded areas to avoid diseases. Further home bases in high rainfall area move their towards low rainfall regions during the SW monsoon and back during NE rains. Summer pastures are seeked in deep western hill shadows of the western ghats, up until Shimoga.

![](https://i.imgur.com/5OxlwFb.png =604x480)




### Gallery 

Below are some of the maps work in progress with annotations and some close to complete.

##### Gujarat


![](https://i.imgur.com/JVVxzZ0.png =960x480)

![](https://i.imgur.com/dFwyjzk.png =480x330)

##### Uttarakhand

![](https://i.imgur.com/zpDTwi9.jpg)

##### Tamilnadu

![](https://i.imgur.com/INexvKe.png =480x480)

##### Leh and Ladakh

![](https://i.imgur.com/FJMgCQj.png =612x480)

![](https://i.imgur.com/osqyRzS.png =676x480)


## Credits
* CFP team and associated researchers
* Janastu Team (Yatharth, Micah, Athithya, Shalini, Shafali, Bhanu, Rishi)
* Gopi Krishna - Mitan Handicrafts


## References
Other links and references here: [https://open.janastu.org/projects/pastoral](https://open.janastu.org/projects/pastoral)

[General mapping https://twitter.com/PratapVardhan/status/1496342917849686016](https://twitter.com/PratapVardhan/status/1496342917849686016) 
