[![endorse](https://api.coderwall.com/pwldp/endorsecount.png)](https://coderwall.com/pwldp)

# leaflet.viewcenter


This is a simple extension of Leaflet.Control.Zoom that adds a change localization and zoom button above the zoom in and zoom out controls.


Checkout the [demo](http://pwldp.github.io/leaflet.viewcenter/).


## USAGE


Be sure to include the *leaflet.viewcenter.js* script somewhere after Leaflet is loaded.

    <script src="http://cdn.leafletjs.com/leaflet-0.6.4/leaflet.js"></script>

    <link rel="stylesheet" href="leaflet.viecenter.css" />
    <script src="leaflet.viewcenter.js"></script>


Do all your normal Leaflet [initialization stuff](http://leaflet.cloudmade.com/examples/quick-start.html), except make sure that you initialize the map *without* the default zoom controls:

    <!-- map container -->
    <div id="map"></div>

    // init map
    var map = new L.Map('map');

    // init ViewCenter plugin
    var viewCenter = new L.Control.ViewCenter();
    map.addControl(viewCenter);


## NOTES


This extension was built and tested for Leaflet version 0.6.4.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/pwldp/leaflet.viewcenter/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

