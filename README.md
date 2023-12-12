# stac_demo

## SPECS

STAC specs: https://github.com/radiantearth/stac-spec/

STAC API specs: https://github.com/radiantearth/stac-api-spec

Presentation: https://youtu.be/Ugazf5bWsGE?feature=shared

## Sample Static catalog of gemeente Utrecht (trees)

https://bertt.github.io/stac_demo/catalog.json

in STAC Browser: https://radiantearth.github.io/stac-browser/#/external/bertt.github.io/stac_demo/catalog.json

in Python Notebook: [stac_demo.ipynb](stac_demo.ipynb)

## OGC Standard

https://www.ogc.org/requests/ogc-seeks-public-comment-on-adoption-of-stac-and-stac-api-as-community-standards/

## Validating STAC

https://staclint.com/

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

