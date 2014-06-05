# Seattle Atlas

Provides convenient method to download Seattle related shapefiles and convert some of them to TopoJSON format.

Inspired by Bostock's [world-atlas](https://github.com/mbostock/world-atlas). 

Idea copied from and based on Justin Palmer's [portland-atlas](https://github.com/Caged/portland-atlas).

## Prerequisites

Before you can run `make`, you’ll need to install `Node` and `ogr2ogr`. If you are on Mac OS X, and using [Homebrew](http://mxcl.github.com/homebrew/) then just run:

```bash
brew install node 
brew install gdal
```

And then, from this repository’s root directory, install the dependencies:

```bash
npm install
```

## Make Targets

<b>shp/osm.shp</b>

Shapefiles from [Metro Extracts](http://metro.teczno.com/#seattle).