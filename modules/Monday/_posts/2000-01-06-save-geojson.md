---
title: Save GeoJSON
---

## Save as GeoJSON or shapefile
*5 minutes*, included in the live session if you attend

Now that you have imported your locations into QGIS, we recommend that you save them as a geospatial file, either in GeoJSON format, or shapefile if you prefer

If your locations were originally imported as a .gpx file, you only need to save the 'name' field in your export file - this is the field that contains the WPT name

> 1. Right-click on your locations file (.gpx, .txt or .csv) > `Export` > `Save Features As...`
2. Choose the file `Format`: GeoJSON or ESRI Shapefile 
3. Click the `...` button beside `File name` to specify a location and name for your new file 
4. For .gpx files only, click on `Deselect All` then click the checkbox beside '`name`' to ensure we save the WPT names.  Click OK to save your file
5. Remove the original .gpx file from your project: right-click on it > `Remove Layer...`

---

- Right-click on your locations file (.gpx, .txt or .csv) > `Export` > `Save Features As...`
<center><img src="{{site.baseurl}}/img/save-geojson-qgis-044.png" alt="QGIS screenshot: Save features"></center>

<br>

- Choose the file `Format`: GeoJSON or ESRI Shapefile 
<center><img src="{{site.baseurl}}/img/save-geojson-qgis-051.png" alt="QGIS screenshot: Choose GeoJSON"></center>

<br>

- Click the `...` button beside `File name` to specify a location and name for your new file 
<center><img src="{{site.baseurl}}/img/save-geojson-qgis-075.png" alt="QGIS screenshot: Name your file"></center>

<br>

- For .gpx files only, click on `Deselect All`
<center><img src="{{site.baseurl}}/img/save-geojson-qgis-082.png" alt="QGIS screenshot: Deselect all columns"></center>

<br>

- Click the checkbox beside 'name' to ensure we export the WPT names
<center><img src="{{site.baseurl}}/img/save-geojson-qgis-090.png" alt="QGIS screenshot: Select name column"></center>

<br>

- Remove the original .gpx file from your project: right-click on it > `Remove Layer...`
