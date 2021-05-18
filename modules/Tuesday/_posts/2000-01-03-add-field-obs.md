---
title: Import field obs
---

## Add your field observations to QGIS
*15 minutes*

Re-open the QGIS project that contains the waypoints you imported previously, and **import your field data** by following the steps below

Note that *nothing will be drawn on the map* after this stage!  Our spreadsheet lacks coordinate data, so QGIS cannot draw features on the map, but your field observations are stored and visible as a data table, ready to be joined to the waypoints in the next module

The final step below is to open the attribute table to check your data imported correctly.  Do they look the same as in the original .csv file?

> 1. `Layer > Add Layer > Add Delimited Text Layer...`
1. Choose source file - click the `...` button
2. Ensure `No geometry (attribute only table)` is selected under `Geometry Definition`, then click `Add` and `Close`
3. Right-click on layer in Layers tab > `Open Attribute Table`
4. Check that your imported records look sensible

<br>

---

Instructions including screenshots:
- `Layer > Add Layer > Add Delimited Text Layer...`
<center><img src="{{site.baseurl}}/img/add-obs-qgis-017.png" alt="QGIS screenshot: Add delimited text layer"></center>

<br>

- Choose source file - click the `...` button
<center><img src="{{site.baseurl}}/img/add-obs-qgis-038.png" alt="QGIS screenshot: Select file"></center>

<br>

- Ensure `No geometry (attribute only table)` is selected under `Geometry Definition`, then click `Add` and `Close`
<center><img src="{{site.baseurl}}/img/add-obs-qgis-050.png" alt="QGIS screenshot: No geometry definition"></center>

<br>

- Right-click on layer in Layers tab > `Open Attribute Table`
<center><img src="{{site.baseurl}}/img/add-obs-qgis-068.png" alt="QGIS screenshot: Save features"></center>

<br>

- Check that your imported records look sensible
<center><img src="{{site.baseurl}}/img/add-obs-qgis-070.png" alt="QGIS screenshot: Save features"></center>