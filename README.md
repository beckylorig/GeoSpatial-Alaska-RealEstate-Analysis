# Geospatial Analysis of Alaska Real Estate Properties using Python


### The focus of this project is to ensure proper loading of GIS data into Postgres database (using PostGIS functionality), querying the stored data, and accessing it in Python for spatial analysis.

## Main Processing Steps
#### PostgreSQL Database

    Set up PostGIS and spatial extensions within the database

#### Installing libraries

    - geopandas - geo dataframe
    - shapely - geometry
    - contextily - viewing basemaps
    - osgeo/gdal open source geospatial, GDAL translator library for raster and vector geospatial data formats

#### GIS

    - import shapefile
    - convert geometry from WKT format into PostGIS format for database storage
    - query centroids (center of polygons to get points)
    - convert WKB PostGIS format back into WKT format for mapping

#### GIS Data - shapefiles

    - Fire Stations
    - property info (spatial)
    - property info (non-spatial)
    - census tracts
    - census tract rental pricing (2015 data)
    - census tract median income (2015 data)

