# Los Angeles Field
This repository contains digitized map data for the Los Angeles oil field, as it appeared in April, 1903.

This repository contains the digitized 1903 Los Angeles City Field map. Note, this map contains only wells and related structures that were observed in the Los Angeles FIELD in April, 1903. These files do not cover the entire Los Angeles BASIN. 

The files are:

*Los Angeles Field database diagram.pdf*: This ERD is useful for understanding the relationships among the tables.

Los Angeles Field georeferenced 1903 map, east and west: These are georeferenced raster GeoTIFF files.

Los Angeles Field point features ESRI shapefile: For those needing an ESRI shapefile, here it is. Attribute data is in the Los_Angeles_Field.db SQLite file. Join using the link_id field.

Los Angeles Field wells.gpkg: This is a QGIS geopackage that contains the vector point file and the two georeferenced raster scans. For QGIS users, this might be the best choice. Join the vector layer with the Los_Angeles_Field.db SQLite file on the link_id field. 

Los_Angeles_Field.db: This is a SQLite file containing the well, tank, and plant attribute data.

Register of Oil Wells in the Los Angeles Field.pdf: This is the source of the attribute data. 
