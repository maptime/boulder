---
layout: event
category: event
title: "Creating fun graphics with OSM data!"
rsvp: https://www.meetup.com/Maptime-Boulder/events/250619869/
date: 2018-06-07 18:00
permalink: osm-data-fun
author: Diane Fritz
---

We're going to be artsy this month! We'll use OSM data to create screen-print designs!!! You can use these to make your own T-shirts, skirts, pillows or whatever you'd like! Many people are putting OSM data on clothing, posters, etc. Let's look at some simple ways to create these graphics with QGIS.

Come with tools that enable you to get OSM data into graphics files, like a laptop loaded with QGIS and the QuickOSM plugin. We'll collectively figure out fun ways to do this. Or bring just a sketch pad if you want to be inspired and play with ideas on paper to work on later. For inspiration, look at what others have done printing OSM data on clothes: [http://maponshirt.com](http://maponshirt.com), [https://flowingdata.com/2014/12/03/map-print-clothing/](https://flowingdata.com/2014/12/03/map-print-clothing/)

And yes, that's a picture of a cake... you can screen print cakes, I've heard... there just might be cake.

-Your Maptime Boulder Organizers

NOTE: We won't be hosting a July 5th meetup as many folks will be out of town.


# Instructions + Notes
The goal of tonight's meetup is to install and explore the abilities of QGIS for styling and representing data from OpenStreetMap. 

What's special about OSM data? It has a little bit of everything. Want a pretty good street network? Sure. Want endless amounts of metadata to filter and style off? Absolutely! 

### 1. Install QGIS
QGIS (QuantumGIS) is an Open-Source GIS software available on all platforms. [Download Page](https://qgis.org/en/site/forusers/download.html)

###### _QGIS 2 or QGIS 3_?

If you have experience with using QGIS 2, I recommend sticking with what works and you're familiar with... 

### 2. Install a plugin to handle [OpenStreetMap](http://openstreetmap.org) data
There are a variety of tools to get OSM data into QGIS. 
[QuickOSM](https://plugins.qgis.org/plugins/QuickOSM/) is a popular one. If you already have an OSM file, QGIS can import the file with a limited schema (limited metadata).


##### Rather download larger chunks of OSM data?
* GeoFabrik makes Country / Regional level extracts [available here](http://download.geofabrik.de/)

For simplicity, and if you'd like to incorporate more metadata, here are two files to start with: both Denver and Boulder. These have all OSM attributes... 

[Boulder](/boulder/assets/geojson/boulder.geojson.zip)

[Denver](/boulder/assets/geojson/denver.geojson.zip)


### 3.Load into QGIS and Filter/Style

Instructions here will vary based on your data and version of QGIS.





_Last Edited by Jennings, June 7, 2018_