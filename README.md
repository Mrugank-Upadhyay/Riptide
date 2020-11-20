# Riptide

## NASA Space Apps Challenge 2020 Hackathon Project

## Summary

Riptide is a sophisticated yet elegant web application designed to simulate floods all around the globe. Given a location, intensity and duration, Riptide can graphically demonstrate the various effects of a flood. With a user-focused design, anyone is able to learn about the population displaced, and total damage caused by inundation thanks to an intuitive and clean interface. Using topographical and population data from NASA Jet Propulsion Laboratory along with a custom made algorithm, Riptide generates a rendition of coordinates that describe the flow of water after a certain duration.

Follow this link to our Riptide Presentation: https://docs.google.com/presentation/d/1RETNpOlutAkVhuFRoyFCiDfbgYqjcj9PlFVa9uu2xmI/edit?usp=sharing

### The team

Front-End:
Mrugank Upadhyay & Abbiram Ramanathan

Back-End:
Siddharth Gupta & Dev Parikh

## Achievements

Created an aesthetically pleasing, interactive map with search functionality, sliders for elapsed time and flood intensity, and flood simulation
Developed an algorithm to determine spread of a flood based on an epicentre, topological data, duration and intensity
Determined affects of water damage based on cost of construction and population density

## How We Addressed This Challenge

As climate change accelerates the frequency and intensity of floods, understanding how vast amounts of water may harm our infrastructure and people is essential to developing a secure future. Unfortunately, most floods hit developing and underdeveloped nations, those which often lack the resources for emergency preparedness. High-quality flood models have high barriers to entry, making it a luxury for only the nations which can afford it. Our software reduces those barriers as medium-resolution topography data is provided by NASA, we can make models for flood impacts, and provide them to those who need it the most, saving countless lives.

## How We Developed This Project

### Front-End

Utilized ReactJS and Mapbox GL to create website components and map
Added map search functionality by implementing the Geocoder API
Added user controlled sliders by implementing the Slider ReactJS API
Added data-driven points to identify flood points using GeoJSON & MapBox GL Feature Collection

### Back-End

Utilized NASA SRTM topology maps in order to create a height map of the area, an algorithm to model water flow.
Added population displaced and total damage done, based on population density, and structural engineering of the given city, and it's corresponding boroughs.
Stored information in JSON format to be easily parsed by React.

### Tools / Tech

ReactJS
MapBox GL JS
MapBox Studio
NumPy

### Difficulties

Implementing a flood simulation overlay with features
Curation of relevant and optimal data sets
Implementing a server to submit requests from the Map Interface to Back-end algorithm to receive JSON co-ordinate points
Developing a realistic algorithm to simulate the spread of water based on topological data
