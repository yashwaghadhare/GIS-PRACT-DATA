Practical 6 (A) : 
	1. add vector layer IND_adm => IND_adm0.shp
	2. In OSM place search , search mumbai and double click on mumbai metro
	3. then click layer =>  georeference and then open raster img i.e. bombay_1909 
	4. click setting transform and select type => thin plate.. , resampling method => nearest neighbour and uncheck all the checkbox and hit ok..
	5. then add 4 points and Done...!!


Practical 6 (B) :

	1. add open streetmap 
	2. go to properties select CRS 3857
	3. OSM search search gateway of india 
	4. then click layer =>  georeference and then open raster img i.e. Gateway arial imagery 
	5. click setting transform and select type => thin plate.. , resampling method => nearest neighbour and uncheck all the checkbox and hit ok..
	6. then add 4 points and Done...!!


Practical 6 (C) :

	1. Add raster image Christchurch TOPO50.tif
	2. Right click => properties => pyramid => select all 4 resolution and appl and ok
	3. click on setting => option => digitizing => change the color 
	4. create layer new spatialite layer 1st save database i.e mydbsqlite then layer name i.e. digitized_row then type line , epsg 4167 and new field name = name and type textdata and add to field list then same add class and hit ok
	5. then draw road and go to symbology and edit roads then click on show label