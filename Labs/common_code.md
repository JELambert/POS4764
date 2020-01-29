# Common Code

This is basic cheat sheet for code that will be used throughout the labs.

### Packages
Packages make up the backbone of python coding.

* import pandas as pd
* import os
* import geopandas as gpd

### Universal statements
* print("string") or print(var_name)
* help(package) ex. help(pd)


### OS operations
* os.getcwd() -- Returns the current working directory
* os.chdir('') -- whatever is put into the '' will be the new directory.



### Pandas operations
* df = pd.read_csv('') -- reads a csv file and stores it in df.
* df.head() -- shows the top of data frame (default is 5 rows)
* df.tail() -- shows the bottom of data frame (default is 5 rows)
* df.describe() -- 
