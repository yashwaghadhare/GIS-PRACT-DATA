Practical 4(A) :: 

	Step 1 :: Add vector layer ne_10m_populated_places_simple.zip
	Step 2 :: Right click and select openattribute table 
	Step 3 :: Open expression and write [ "pop_max" > 100 and "pop_min" < 10000 ]


Practical 4(B) :: 

	Step 1 :: Add raster image "10n060e_20101117_gmted_mea300.tif"
	Step 2 :: zoom the top corner by co-ordinate
	Step 3 :: Go to raster => extraction => clip raster by extend and then cliping extend => select use map canvas then save file and run
	Step 4 :: Go to raster => extraction => contor and then change interval betn contor line is 100.0000000 then save file and run
	Step 5 :: Go to Propertie (...._counter file that saved in step 4) then click lables and select single labels value shold be ELEV then width 0.10 and change color accordingly
	Step 6 :: Open aattribute table then click 1st row and click on search or zoom icon
	Step 7 :: then we have to save file so click on layer and click save layer as change format to KML 
	Step 8 :: CLick on raster => analysis and select hillshade..
	Step 9 :: Input layer ( step 3 layer ) then save this file and run
	step 10 :: click on properties (step 9) layer and select symbology then render type singleband pseudocolor then interpolation linear then color click on all color ramps and choose any color and click apply and ok

