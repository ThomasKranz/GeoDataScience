By this short introduction using geospatial data in Python I combine three different types of data sources which can be implemented in one map. For this purpose I start with reading a .csv with random adresses in order to request geo coordinates from Google using its API and creating a new dataframe. I continue reading a zip folder into python with data from Natural Earth and geocode my first dataframe into a geo dataframe with the characteristics of geometry. It´s possible as well to construct a geodataframe manuelly by geopandas. Reading then geo spatial data from GeoJSON allows me to gain more exactly Polygons of the German districts for plotting them with previous geo dataframes into a unique map. 

In a 2nd jupyter notebook I continued with Agglomerative and K-Means Clustering for the gdp per capita data by manipulating the Natural Earth data sheet. 

In a following project I plan to start with SVM algorithms on these geo data.

view file "Using Geo Data in Python": https://bit.ly/2SN3oTl 

view file "Agglomerative and Kmeans Clustering": https://bit.ly/2SN3D0H

