# leaflet.viewcenter


This is a simple extension of Leaflet.Control.Zoom that adds a change localization and zoom button above the zoom in and zoom out controls.


## USAGE


Be sure to include the *leaflet.viewcenter.js* script somewhere after Leaflet is loaded.

    <script src="http://cdn.leafletjs.com/leaflet-0.6.4/leaflet.js"></script>
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
