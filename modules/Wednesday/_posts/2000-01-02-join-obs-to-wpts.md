---
title: Join data
---

## Join location coordinates to field records
*20 minutes*

We've laid the groundwork, and now we're ready to **join our two datasets** together!  :raised_hands:

The instructions below are written for the water beetle example data, but we encourage you to do this exercise on your own field data if you can, adapting the instructions as you go.  You might find it useful to run through the exercise with the example data first, to get familiar with the process 

Both of our example files have a column called 'WPT', which contains the waypoint name saved on the GPS.  This allows us to **match** water beetle survey records to the location at which they were collected 

Note that it's possible to join the layers in *either direction*, choosing either file as the source or destination.  The consequences would be as follows:
1. Join field survey data (source) to waypoints (destination) - QGIS matches the *first* field record it finds to each waypoint in the file.  This option makes sense if you only have a single record (row in your field observations spreadsheet) for each waypoint, and you want to discard any observations that don't have a corresponding waypoint   
2. Join location coordinates (source) to field records (destination) - every field observation will have the corresponding survey coordinates attached to it, and waypoints without survey data will be ignored

The water beetle dataset contains multiple records for each survey location, so we are going to use the **second approach** today, adding location coordinates (Latitude & Longitude) from our *source* layer of waypoints to our *destination* layer of beetle survey data

> 1. Right-click on 'waterbeetles_fieldobs.csv' > `Properties`
2. Click `Join` in the left-hand list to open the Join tab
3. Click the `green '+'` at the bottom of the dialogue box to add a new join
4. Select the `Join layer`; the source layer which contains the data you want to add to your destination layer; in this case, it's the geoJSON of waypoints
5. Specify the `Join field` - the column of unique location identifiers (WPT) in your source layer
6. Specify the `Target field` - the column of unique identifiers (WPT) in your destination layer
7. Under `Joined fields`, select which fields you want to join from your source to your destination layer - click the checkboxes beside Latitude and Longitude
8. Under `Custom field name prefix`, choose whether to prepend a phrase indicating from which dataset these records were joined.  With our example dataset, you can delete this prefix to keep the column names short
9. Click `OK` and `Apply` to apply the join
10. - Check the **join worked correctly** by opening the attribute table of the water beetle field obs layer - right-click > `Open Attribute Table`)
11. Do Latitude and Longitude now appear in each record?

---

- Right-click on 'waterbeetles_fieldobs.csv' > `Properties`

<center><img src="{{site.baseurl}}/img/qgis-join-008.png" alt="QGIS screenshot: Open layer properties"></center>

<br>

- Click `Join` in the left-hand list to open the Join tab
<center><img src="{{site.baseurl}}/img/qgis-join-009.png" alt="QGIS screenshot: Join tab"></center>

<br>

- Click the `green '+'` at the bottom of the dialogue box to add a new join

<center><img src="{{site.baseurl}}/img/qgis-join-010.png" alt="QGIS screenshot: Add new join"></center>

<br>

- Select the `Join layer`; the source layer which contains the data you want to add to your destination layer; in this case, it's the geoJSON of waypoints

<center><img src="{{site.baseurl}}/img/qgis-join-011.png" alt="QGIS screenshot: Specify join layer"></center>

<br>

- Specify the `Join field` - the column of unique location identifiers (WPT) in your source layer

<center><img src="{{site.baseurl}}/img/qgis-join-013.png" alt="QGIS screenshot: Specify join field"></center>

<br>

- Specify the `Target field` - the column of unique identifiers (WPT) in your destination layer

<center><img src="{{site.baseurl}}/img/qgis-join-015.png" alt="QGIS screenshot: Specify target field"></center>

<br>

- Under `Joined fields`, select which fields you want to join from your source to your destination layer - click the checkboxes beside Latitude and Longitude

<center><img src="{{site.baseurl}}/img/qgis-join-020.png" alt="QGIS screenshot: Select fields to add"></center>

<br>

- Under `Custom field name prefix`, choose whether to prepend a phrase indicating from which dataset these records were joined.  With our example dataset, you can delete this prefix to keep the column names short

<center><img src="{{site.baseurl}}/img/qgis-join-030.png" alt="QGIS screenshot: Specify custom prefix"></center>

<br>

- Click `Apply` to apply the join, and `OK` to close the dialogue box

<center><img src="{{site.baseurl}}/img/qgis-join-054.png" alt="QGIS screenshot: Apply join"></center>

<br>

- Check the **join worked correctly** by opening the attribute table of the water beetle field obs layer - right-click > `Open Attribute Table`)

<center><img src="{{site.baseurl}}/img/qgis-join-064.png" alt="QGIS screenshot: Open attribute table"></center>

<br>

- Do Latitude and Longitude now appear in each record?

<center><img src="{{site.baseurl}}/img/qgis-join-074.png" alt="QGIS screenshot: Check Latitude and Longitude"></center>
