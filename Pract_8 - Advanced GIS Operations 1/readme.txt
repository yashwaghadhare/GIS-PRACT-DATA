Practical 8-(A) :: 
    1. Add vector layer ne_10m_populated_places_simple 
    2. Add delimited text layer earthquakes_2021_11_25_14_31_59_+0530.tsv file format :: custom : check only tab then geometry point co-ord xfield : longitude , yfield : latitude and click Add
    3. Go to processing => toolbox => search "remove" then click on "remove null geometry" then select earthquakes_2021_11_25_14_31_59_ then check also remove empty geometry then click run and close
    4. Go to processing => toolbox => search "distance" then click on "distance nearest hub (line to hub)" select source : non null geometry then destination : ne_10m_populated_places_simple then name then kilometers then save file as eq_with_nearest_city.gpkg click run and close.
    5. Done..!!

Practical 8-(B) :: 
    1. Add raster layer us.tmax_nohads_ll_20140525_float.tif then add dilimited text layer 2013_Gaz_ua_national.txt then select custom : tab , then point co-ord then x: INTPTLONG , y: INTPTLAT and add and close 
    2. Install plugin "Point sampling tools" 
    3. Go to plugin => analyses => point sampling tool then select 1st 2nd and last with control and left click then browse and save file as max_temp_at_urbon_location.shp then click ok and close
    4. then uncheck 2013_Gaz_ua_national
    5. Click on identify feature and click anywhere it shows results take a screen shot
    6. remove / uncheck 2013_Gaz_ua_national and max_temp_at_urbon_location
    7. Then add vector layer tl_2013_us_county.zip
    8. right click on tl_2013_us_county then export save vector layer as then file name save counties.shp then CRS 4326 then check add saved file to map checkbox and click ok 
    9. then search in bottom zonal statistics click and then select 1st counties.shp then us.tmax_nohads_ll_20140525_float then band 1 (Gray) then ZS_ then click run and close 
    10. then right click and go to properties of Zonal statistics layer then symbology select top most dropdown as graduated then value ZS_mean then color ramp select anything then mode equal interval then click classify then apply and ok. 

Practical 8-(C) ::
    1. add vector layer shapefile.zip then click add then click arlington_soundings_2002 and Boundary2004 click add layers then select north america then click close 
    2. then go to search bottom last and search tin interpolation then click on that then select 1st shape file arlington_soundings_2002 then elvation then click + then linear then select calculate from layer then select arlington_soundings_2002 then pixel size X : 5 then save file as elevationtin.tif and click run and close 
    3. Go to raster then clip raster by mask layer then select 1st elevation_tin then Boundary2004 then save file as elevationtinclipped.tif then run and close 
    4. select elevationtinclipped.tif right click properties then symbology then singleband_pseudocolor then band 1 (Gray) then min 500.70 and max 546.419 then linear then select color then select mode as equal interval theen classify apply and ok
    5. Go to raster => extraction => contour then just set interval betn contour line as 5 then save file as contours.gpkg run and close and DONE...!!!!!!!!!
