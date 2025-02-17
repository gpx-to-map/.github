# GPX to map
GPX-to-map is a toolset built to allow you to export map images from any tile provider, and render GPX files.

For now, it consist of :
* A core library build for retriving and drawing maps : https://github.com/gpx-to-map/StaticMap
* An autonomous library that will scan GPX files and generate images : https://github.com/gpx-to-map/gpx-to-map-core

### Result

The default settings will product something similar to this :

![test-composed-gr20.png](doc_resource/test-image.png)

## Contributions

If you want to contribute, please open issues, or fork the repo and open PRs. I will happily answer/review them !

## TODOs

* Use TestContainer for ITs
* Make other image format available (especially SVG)
