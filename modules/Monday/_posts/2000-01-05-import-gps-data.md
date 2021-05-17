---
title: Import GPS locations
---

## Import your GPS locations
*15 minutes*, included in the live session if you attend

The main aim of today is to **import your GPS locations** into your QGIS project.  We assume that you have already downloaded the WPT (waypoints) file from your GPS, or prepared a spreadsheet containing X and Y coordinates

We anticipate that your location data may be in one of several different formats:
1. If your locations are in `.gpx` file format, as **downloaded from a GPS**, go to the [Importing .gpx](#gpx) section below
2. If you have a **spreadsheet containing *only* locations** e.g. `.txt` or `.csv `, go to the [Importing .txt or .csv](#txt) section below
3. If you have a single file with **locations *and* field data combined**, go to the [Combined data](#combined) section below

When importing GPX files, QGIS should automatically recognise the **Spatial Reference System**, otherwise known as the *projection* or *Coordinate Reference System (CRS)*.  However, if you're importing another file format, you will probably need to specify the Spatial Reference System.

If you don't have your own dataset, you can download an example dataset of water beetle survey results from Northern Ireland.  See the **Water beetle dataset** page in the Resources folder above :point_up:

<!-- See the [Water beetle dataset]({% link modules/Resources/_posts/2000-01-01-water-beetle-data.md %}) page in the Resources folder above -->

Remember that you can always ask for assistance in the :raised_hand: [**Help Area**](https://padlet.com/VerdantLearn_LT/GISRefresher2_HelpArea_May2021) for this course if you get stuck


### Importing .gpx
{: #gpx }

Assuming you downloaded your locations as a .gpx file, follow these instructions to add your field locations to your QGIS project

For those of you who are confident with the basics of using QGIS, here are the steps, without screenshots:
> 1. Layer > Add Layer > Add vector layer...
1. Choose source file - click the [...] button
2. Select only the Waypoints (unless you also have tracks and routes in your .gpx file)
3. Click Add and Close

<br>

For those of you who want more detail or visual instructions, here are the steps including screenshots:

- `Layer > Add Layer > Add vector layer...`
<center><img src="{{site.baseurl}}/img/add-vector-qgis-018.png" alt="QGIS screenshot: Add vector layer"></center>

- Choose source file - click the `...` button
<center><img src="{{site.baseurl}}/img/add-vector-qgis-020.png" alt="QGIS screenshot: Choose data source"></center>
<br>
<center><img src="{{site.baseurl}}/img/add-vector-qgis-022.png" alt="QGIS screenshot: Choose gpx file"></center>

- Select only the Waypoints (unless you also have tracks and routes in your .gpx file)
<center><img src="{{site.baseurl}}/img/add-vector-qgis-033.png" alt="QGIS screenshot: Only import waypoints"></center>

- Click `Add` and `Close`

### Importing .txt or .csv
{: #txt }

If your location data are in a spreadsheet format, save them either as:
- *tab-delimited* spreadsheets (**.txt**), where columns are separated by a tab character, or
- *comma-delimited* (**.csv**), with columns separated by a comma

It's your choice which format to use; whichever you are most comfortable with, or works best depending on e.g. regional use of commas to indicate decimal places

For those of you who are confident with the basics of using QGIS, here are the steps without screenshots:
> 1. `Layer > Add Layer > Add Delimited Text Layer...`
1. Choose source file - click the `...` button
2. Ensure `Point coordinates` is selected under `Geometry Definition`, and specify which columns contain the X and Y coordinates 
3. Click `Add` and `Close`

<br>

For those of you who want more detail or visual instructions, here are the steps including screenshots:

- `Layer > Add Layer > Add Delimited Text Layer...`

<center><img src="{{site.baseurl}}/img/add-text-qgis-013.png" alt="QGIS screenshot: Add delimited text layer"></center>

- Choose source file - click the `...` button
<center><img src="{{site.baseurl}}/img/add-text-qgis-019.png" alt="QGIS screenshot: Choose text file"></center>

- Ensure `Point coordinates` is selected under `Geometry Definition`, and specify which columns contain the X and Y coordinates 
<center><img src="{{site.baseurl}}/img/add-text-qgis-033.png" alt="QGIS screenshot: Specify X and Y columns"></center>

- Click `Add` and `Close`


### Combined data
{: #combined }

You're in luck!  :sweat_smile:  As you have a single file containing combined location data and field observations, you can complete the work for Monday, Tuesday *and* Wednesday in a single step!

Follow the instructions in the [Importing .txt and .csv](#txt) section above