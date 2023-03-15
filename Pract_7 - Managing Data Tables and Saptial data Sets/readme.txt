Practical 7(A) :: 

	1. Add vector layer tl_2013_06_tract.zip 
	2. Add delimited text layer ca_tracts_pop.csv ,, file format : Custom delimiters select semicolon, comma ,, Geometry 	Definition : No geometry and add that layer.
	3. Go to properties (tl_2013_06_tract.zip) click joins ,, join layer : ca_tracts_pop ,, join field : GEO.id2 ,, Target 	field : GEOID and hit  ok
	4. Go to symbology select value ca_tracts_pop...
	5. Select precision 0 and select Mode :: Equal Interval and edit color range and classify 
	6. uncheck the trim checkbox
	7. select mode : Equal Interval
	8. click classify apply and ok

Practical 7(B) :: 

	1. Add two vector layer OEM_NursingHomes_001 && nybb (.shp) files
	2. Go to vector => Data management tool => Join attribute by location => select 1st nybb then features : intersect then OEM and then select all field and click run
	3. done..!! click (i) button and see the output.

Practical 7(C) :: 

	1. Add delimited text layer file format custom and select tab then geometry type click point co-ord and then x-field LONGITUDE and y-field LATITUDE  then select 4326 EPSG and click add.
	2. Add vector layer ne_10m_admin_0_countries — ne_10m_admin_0_countries.shp
	3. GO to vector => Analysis tool => count points then select 1st ne_10m... layer then select earthquakedatabase then weight field location name then class field country then save as EQCounty.shp and click run
	4. Done..!!

Practical 7(D) :: 

	1. Add vector layer ne_10m_populated_places_simple && e_10m_rivers_lake_centerlines 
	2. Go to properties of ne_10m_populated_places_simple click Filled marker and select symbol layer type filled marker and click apply and ok 
	3. vector => Geo-processing-tools => Buffer => select river layer and then distance 0.02 then click run and close
	4. Turn on show label option for River buffer file that you saved in step 3
	5. Go to vector => Research => select by location => select 1st as River buffer then select checkbox as intersect then select ne_10m_populated_places_simple and run and close
	6. Then zoom layer and see the output and Done..!!😁😁