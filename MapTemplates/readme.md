# Maps
In this folder, you will find some useful code examples with Leaflet as the JavaScript framework for coding maps, and different map constructors (OpenStreetMap and Kartverket).

I suggest going through the different [Leaflet tutorials](https://leafletjs.com/examples.html) and getting to know the [documentation](https://leafletjs.com/reference.html).

## Basic map
This example show the basic initiation of a map with Leaflet and OpenStreetMap. It also sets a center of the map, along with a marker to highlight the center of the map.

## List of Markers
This example show how we can use common JavaScript in conjunction with Leaflet to easily mark all the Rema 1000 grocery store locations in Halden. Here we also use **custom icons as markers**, by taking a Rema "R" symbol logo as a PNG-file and applying the [custom icons from the leaflet documentation](https://leafletjs.com/examples/custom-icons/). It also applies a popup for each marker indicating which Rema 1000 store is shown.

## List of Markers with navigation
This is an expanded example of List of Markers, where we use the dataset to generate navigation (a list of places with buttons) that utilize the [flyTo()-method](https://leafletjs.com/reference.html#map-flyto) in Leaflet to animate and zoom in to the specific places.

## Map with GeoJson
In this example, it is shown how we can add shapes (polygons etc) to highlight selected areas of a map. A GeoJSON object can consist of multiple shapes (called "Features") with each it's own set of properties (like name, content for popups and info).

To create the GeoJSON objects (shapes and properties), I suggest using [GeoJSON.io](http://geojson.io/), which allows you to draw shapes on top of an actual map for precision. Also, check the [Leaflet documentation on GeoJSON](https://leafletjs.com/examples/geojson/).

## Map with Karverket Tiles and Data
This example show how you can use Kartverket as a map constructor. This is useful if you are going to use data from Kartverket in any of your projects.