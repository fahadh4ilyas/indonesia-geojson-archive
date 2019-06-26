# indonesia-geojson-archive
This repository contains geoJSON files about Indonesia from country to villages

## About
These geoJSON files are the most update data from Indonesia. There are 5 geoJSON files which are:
1. Indonesia as a whole country geoJSON.
2. Indonesia's provinces (includes North Kalimantan) geoJSON.
3. Indonesia's cities/regencies geoJSON.
4. Indonesia's sub-districts geoJSON.
5. Indonesia's villages/urban communities geoJSON.

## Source
The files' source are from https://gadm.org/

## What's Changed from Source?
1. Rename some feature's `"NAME_1"` properties from `"Kalimantan Timur"` to `"Kalimantan Utara"` from geoJSON feature.
2. Rename `"NAME_1"` properties from `"Jakarta Raya"` to `"DKI Jakarta"` from geoJSON feature.
3. Rename `"NAME_1"` properties from `"Yogyakarta"` to `"DI Yogyakarta"` from geoJSON feature.
4. Rearrange `"id"`, `"fid"`, `"GID_2"`, `"GID_3"`, and `"GID_4"` properties from geoJSON feature.
5. Split `"Kalimantan Timur"` feature into 2 features, `"Kalimantan Timur"` and `"Kalimantan Utara"`.
