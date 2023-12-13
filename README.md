# stac_demo

## SPECS

STAC specs: https://github.com/radiantearth/stac-spec/

STAC API specs: https://github.com/radiantearth/stac-api-spec

Presentation: https://youtu.be/Ugazf5bWsGE?feature=shared

## Sample Static catalog of gemeente Utrecht (trees)

https://bertt.github.io/stac_demo/catalog.json

in STAC Browser: https://radiantearth.github.io/stac-browser/#/external/bertt.github.io/stac_demo/catalog.json

in Python Notebook: [stac_demo.ipynb](stac_demo.ipynb)

Sample asset:

```
 "assets": {
            "pois.geojson":{
               "type":"application/geojson",
               "href":" https://bertt.github.io/opendata/netherlands/arnhem/pois.geojson",
               "created":"2016-06-01T07:10:11.509271Z",
               "updated":"2016-06-01T06:19:31.383374Z",
               "proj:epsg":4326
            }
 },
```

## File mediatypes

https://pystac.readthedocs.io/en/latest/api/media_type.html

```
COG = 'image/tiff; application=geotiff; profile=cloud-optimized'
FLATGEOBUF = 'application/vnd.flatgeobuf'
GEOJSON = 'application/geo+json'
GEOPACKAGE = 'application/geopackage+sqlite3'
GEOTIFF = 'image/tiff; application=geotiff'
HDF = 'application/x-hdf'
HDF5 = 'application/x-hdf5'
HTML = 'text/html'
JPEG = 'image/jpeg'
JPEG2000 = 'image/jp2'
JSON = 'application/json'
KML = 'application/vnd.google-earth.kml+xml'
PARQUET = 'application/x-parquet'
PDF = 'application/pdf'
PNG = 'image/png'
TEXT = 'text/plain'
TIFF = 'image/tiff'
XML = 'application/xml'
ZARR = 'application/vnd+zarr'
```

## OGC Standard

https://www.ogc.org/requests/ogc-seeks-public-comment-on-adoption-of-stac-and-stac-api-as-community-standards/

## Extensions

https://github.com/stac-extensions/

Web Map Links:

https://github.com/stac-extensions/web-map-links

```
3D Tiles, 
OGC WMS
OGC WMTS
PMTiles
TileJSON
XYZ

  "links": [
    {
      "href": "https://storage.googleapis.com/open-cogs/planet-stac/cocabamba-peru/3d-geofox.ai/3DTiles/tileset.json",
      "rel": "3d-tiles",
      "title": "3D Tiles",
      "type": "application/json"
    },
]
```

mogelijke rel types: 3d-tiles, wms, wmts, pmtiles, xyz, tilejson

## Best practices

https://github.com/radiantearth/stac-spec/blob/master/best-practices.md

## Validating STAC

On the Web: https://staclint.com/

Command line: https://github.com/stac-utils/stac-validator

![image](https://github.com/bertt/stac_demo/assets/538812/229ff7c5-1383-4ce0-a98f-14ad1000351e)


## Other STAC Catalogs

Suisse: https://data.geo.admin.ch/api/stac/v0.9

![image](https://github.com/bertt/stac_demo/assets/538812/43768e28-9c88-45a9-8a9d-02754cdabbe5)

Google EarthEngine https://stacindex.org/catalogs/google-earth-engine#/?t=1

![image](https://github.com/bertt/stac_demo/assets/538812/06984a7f-3882-4016-a08c-42e27e96c599)

Microsoft Planetary Computer: https://planetarycomputer.microsoft.com/api/stac/v1

![image](https://github.com/bertt/stac_demo/assets/538812/b30831a2-cee5-4735-be88-52ca128d2b50)

Overview site: https://stacindex.org

## STAC Ecosystem

https://stacindex.org/ecosystem

### GDAL

```
$ gdalwarp "STACIT:\"https://planetarycomputer.microsoft.com/api/stac/v1/search?&collections=usgs-lcmap-conus-v13&datetime=2021-01-01/2021-12-31&bbox=-79.762,40.496,-71.856,45.013\":asset=lcpri" output.tif
```

![image](https://github.com/bertt/stac_demo/assets/538812/c060debf-1586-43ca-a7cb-83e64caf3b7b)

![image](https://github.com/bertt/stac_demo/assets/538812/f0f1e1c1-ff65-4ed5-86ad-34d942a32676)

### QGIS STAC Plugin - STAC API Browser

![image](https://github.com/bertt/stac_demo/assets/538812/d4b73c7e-4619-4716-882d-dab30ca9d224)

### ArcGIS Pro STAC

![image](https://github.com/bertt/stac_demo/assets/538812/57fb7fd2-48c5-4593-9f2f-461d04c79fc0)

