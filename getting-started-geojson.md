---
title: Getting Started with GeoJSON
authors:
- Eli Pousson
date: 2015-12-03
---

# Getting Started with GeoJSON for Historians and Preservationists

This lesson is organized in two parts:

1. An Introduction to GeoJSON (similar to the Programming Historian [Introduction to Google Maps/Google Earth](http://programminghistorian.org/lessons/googlemaps-googleearth) lesson)
2. Creating and modifying maps with geojson.io

# 1: Introduction to GeoJSON

Here are the key questions this lesson should answer:

- What is GeoJSON?
- When can you use GeoJSON instead of shapefiles and ArcGIS?
- Why can you use GeoJSON instead of KML and Google Maps?
- Why is GeoJSON a good format for open source projects?
- What are the limits of GeoJSON in comparison to other map data formats?
- What tools are available for working with GeoJSON data?
	- [geojson.io](http://geojson.io)
	- [dropchop.io](http://dropchop.io)
	- [Mapbox.js](https://www.mapbox.com/mapbox.js/api/v2.2.3/)
	- [Geo for Google Docs](https://github.com/mapbox/geo-googledocs)
	- QGIS and GeoJSON
	- ArcGIS and GeoJSON
	- CartoDB and GeoJSON
- What resources are available for learning more about GeoJSON?

## Related Resources

- [Learn GeoJSON](https://github.com/lyzidiamond/learn-geojson) by Lyzi Diamond
- [Maptime Lessons and Resources](maptime.io/lessons-resources/)


# 2: Creating and modifying maps with geojson.io

What can you do with GeoJSON? So many things! You can create maps for:

- Sharing collection data (e.g. documents, artifacts, photographs)
- Promoting walking, bike or driving tours
- Illustrating digital exhibits created with Omeka, WordPress or HTML
- Visualizing data (e.g. population, economy, housing)

Examples (these are all from [Baltimore Heritage](http://baltimoreheritage.org/) projects – let's find more examples to include!):

- [Tour map](http://baltimoreheritage.org/event/confederate-monuments-wyman-park-dell-charles-village-tour-discussion/) in a WordPress event page
- [Building inventory map](baltimoreheritage.github.io/baltimore-civil-rights-heritage/map) on a GitHub Pages hosted Jekyll site
- [Map of fortifications](http://collection.baltimoreheritage.org/exhibits/show/hampstead-hill/battle-of-baltimore) for an Omeka digital exhibit (see section on Where were the Fortifications?)
- [Historic political boundary map](https://github.com/baltimoreheritage/baltimore-geojson/blob/master/baltimore-city-wards-1797.geojson) in a GitHub repository

## Creating your map data

- Do you need points, areas, or lines?
- What titles and descriptions are you using for your features?
- What other data should you include?
- Are there any standard formats you should use? (e.g. [House Facts Standard](http://www.codeforamerica.org/our-work/data-formats/housefacts/))

## Designing your map

- How much data is appropriate to display? Should the data be simplified?
- What colors should you use?
- What map icons should you use? Learn more about [Maki](https://www.mapbox.com/maki/)

## Distributing your map

- How to use Mapbox.js?
- How to display maps with bl.ocks.org? (e.g. [Confederate Monuments in Wyman Park Dell and Charles Village](http://bl.ocks.org/elipousson/ec22b987c7b2cfad955e))
- How to use iframe embeds?

## Related Resources

- THATCamp Philly: Intro to Web Mapping and Geodata with CartoDB from [Chad Nelson](http://twitter.com/bibliotechy) and [Scott Williams](http://twitter.com/moltude) - [Slides](http://bibliotechy.github.io/cartodb/#/), [Notes](https://docs.google.com/document/d/1QEptlrMKfR9TzklhcWmt33TExxv6sq228pKjmjAu7A0/edit)
- NYPL Labs: [From Paper Maps to the Web: A DIY Digital Maps Primer](http://www.nypl.org/blog/2015/01/05/web-maps-primer)
- [Creating “Lightweight” Digital Maps with GeoJSON Workshop](http://pure.qub.ac.uk/portal/en/activities/creating-lightweight-digital-maps-with-geojson-workshop(cf9ed537-8654-49f0-93ec-8c47bc4d1261).html) (See also: these slides for [Putting You Data on the Map](http://www.slideshare.net/shawnday/putting-your-data-on-a-map)) 
- IUPUI: [Introduction to GeoJSON for the Humanities](http://www.iupui.edu/~iahi/?event=workshop-introduction-to-geojson-for-the-humanities) (this is just the workshop announcement but maybe the materials are available?)
