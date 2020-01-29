# Common Code

This is basic cheat sheet for code that will be used throughout the labs.

### Packages
Packages make up the backbone of python coding.

* import pandas as pd
* import os
* import geopandas as gpd
* from shapely.geometry import Point, LineString, Polygon

### Universal statements
* print("string") or print(var_name)
* help(package) ex. help(pd)
* list = [] ex. list = ['item1', 'item2', 'item3']

### OS operations
* os.getcwd() -- Returns the current working directory
* os.chdir('') -- whatever is put into the '' will be the new directory.



### Pandas operations
* df = pd.read_csv('') -- reads a csv file and stores it in df.
* df.head() -- shows the top of data frame (default is 5 rows)
* df.tail() -- shows the bottom of data frame (default is 5 rows)
* df.describe() -- basic statistics
* df.columns -- lists all column headers
* df.dtypes -- describes the variable types of all columns in df
* pd.set_option('display.max_columns', 100) -- set the display options for columns
* pd.set_option('display.max_rows', 100) -- set the display options for rows



### GeoPandas operations
* gdf = gpd.read_file('filename.shp') -- read a shapefile

### Shapely
* my_first_point = Point(7.4, 1.3) -- Make a point object
1. my_first_point.x -- access x coordinate
2. my_first_point.y -- access y coordinate
