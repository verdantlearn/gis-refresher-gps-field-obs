---
title: Save GeoJSON
---

## Save as GeoJSON or shapefile
*10 minutes*

Now that you have added location coordinates to your field observations, several more steps are needed to **save your layer in a geospatial file format**, so that in future you can add it to your QGIS project as a vector layer in a single step

You have done all of these steps in previous exercises, with the execption of saving your layer as a `Comma Separated Value [CSV]` file.  See if you can complete this exercise without screenshots to assist you, referring back to previous exercises if necessary

> 1. Export your new layer of combined field obs and coordinates as a `Comma Separated Value [CSV]` file - right-click > `Export` > `Save Features As...`
1. Plot your water beetles points again from the new .csv file - `Layer > Add Layer > Add Delimited Text Layer...`
2. `Export` the file again, this time as a GeoJSON or ESRI Shapefile
3. Remove the original table of field observations - right-click > `Remove Layer...`
4. Finally, use the `Identify` tool <img src="{{site.baseurl}}/img/QGIS_IdentifyTool.png" alt="QGIS Identify tool button"> on the QGIS toolbar to check that your data look sensible - click on several points and review the attribute information that pops up

If you're struggling to complete this exercise without the illustrated instructions, add a request for them in the [Help area](https://padlet.com/VerdantLearn_LT/GISRefresher2_HelpArea_May2021)

<!-- 
---

**Add screenshots if requested**

- Export your new layer of combined field obs and coordinates as a `Comma Separated Value [CSV]` file - right-click > `Export` > `Save Features As...`

<center><img src="{{site.baseurl}}/img/qgis-save-join-000.png" alt="QGIS screenshot: Save features"></center>

<br>

- Plot your water beetles points again from the new .csv file - `Layer > Add Layer > Add Delimited Text Layer...`

<center><img src="{{site.baseurl}}/img/qgis-save-join-000.png" alt="QGIS screenshot: Add csv file"></center>

<br>

- `Export` the file again, this time as a GeoJSON or ESRI Shapefile

<center><img src="{{site.baseurl}}/img/qgis-save-join-000.png" alt="QGIS screenshot: Export to GeoJSON"></center>

<br>

- Remove the original table of field observations - right-click > `Remove Layer...` 

<center><img src="{{site.baseurl}}/img/qgis-save-join-000.png" alt="QGIS screenshot: Remove original file"></center>

<br>

- Finally, use the `Identify` tool <img src="{{site.baseurl}}/img/QGIS_IdentifyTool.png" alt="QGIS Identify tool button"> on the QGIS toolbar to check that your data look sensible - click on several points and review the attribute information that pops up

<center><img src="{{site.baseurl}}/img/qgis-save-join-000.png" alt="QGIS screenshot: Use identify tool"></center>-->
