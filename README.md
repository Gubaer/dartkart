# dartkart

_dartkart_ is a framework for web cartografy in the tradition of the
JavaScript libraries [OpenLayers](http://www.openlayers.org) and 
[Leaflet](http://leafletjs.com/). It is neither a 1:1 port of 
them nor does it provide the full functionality of either of them, 
but it has a similar structure and borrows a lot of ideas from them.

## Examples and Demos
See [demos](http://gubaer.github.com/dartkart/demo.html)

## Documentation 
See [API docs](http://gubaer.github.com/dartkart/docs)


## Depend on it
`dartkart` isn't available from [pub.dartlang.org](http://pub.dartlang.org) yet. 

For the time beeing, you can add a dependency to the GitHub repository
to your `pubspec.yaml`.
  
```
dependencies:
  dartkart:
  	git: git://github.com/Gubaer/dartkart.git
```

## Status
This is work in progress. APIs and documentation are unstable. 

Currently supported:

  - a basic map viewport (the coordinate reference system EPSG:4326
    is currently fixed) supporting a stack of layers
  - a basic tile layer for OpenStreetMap map tiles
  - a basic tile layer for WMS sources (provided they accept the SRS
	EPSG:4326)
  - a vector layer displaying Simple Features as SVG	
  - a couple of map controls for panning and zooming the map, for
    displaying the map scale and for a list of layers. 
  

More to come later (hopefully ...)

## Author
Karl Guggisberg <karl.guggisberg@guggis.ch>

## License 
`dartkart` is licensed under the Apache 2.0 license, see files 
LICENSE and NOTICE.