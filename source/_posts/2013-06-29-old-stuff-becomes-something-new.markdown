---
layout: post
title: "Old stuff becomes something new"
date: 2013-06-29 20:51
comments: true
categories: [GitHub, GeoJSON, maps]
---

A few months ago I was working on an app to allow users to look for fast food restaurants in Spain. Actually, the app is pretty much done but I've not published yet because of some minor design details. I'm that kind of a good-eye guy who doesn't want to show the world the product til it's amazing, but I'm becoming more *lean* lately.

I made a web scraper to get fast food restaurants info (as location, name, image,…) and then put into a database (I used MongoHQ btw). So, this weekend I uploaded the [code](https://github.com/willeeh/food-franchises-geojson) to GitHub. 

You can think: it's not a big deal anyway, so why --this boring-- guy is talking about this? 

Here we go… GitHub has launched a [good feature](https://github.com/blog/1528-there-s-a-map-for-that) to visualize geographic data, using [Leaflet.js](http://leafletjs.com/), [MapBox](http://www.mapbox.com/) and [OpenStreetMap](http://www.openstreetmap.org/). Ten days after this announcement they've improved this feature letting [large data sets to be grouped automatically](https://github.com/blog/1541-geojson-rendering-improvements). Wonderful work! 

That day I had no doubts I would use my code to generate GeoJSON to visualize fast food restaurants in Spain. 

What do you think about this result?

<script src="https://embed.github.com/view/geojson/willeeh/food-franchises-geojson/master/ALL_IN_ONE.geojson?height=420&width=700"></script>
