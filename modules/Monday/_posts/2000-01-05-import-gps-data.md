---
title: Import GPS locations
published: false
---

# Steps
1. Add .gpx file (or text file) to project
2. Save as .geojson
   1. Right-click on .gpx > Export > Save Features As...
   2. Format = .geojson
   3. File name: click ... button, choose a location and name 
   4. Only save 'name' field, which contains WPT
3. Add field obs to project
   1. Nothing is drawn on the map
   2. Examine attributes
4. Join field obs to .geojson
   1. Right-click on 'waterbeetles.geojson' > Properties
   2. Join tab
   3. Select correct layer to join
   4. Select correct join column in *which layer?* 
   5. Select correct join column in *which layer?* 
5. Save as .geojson 
   1. Right-click on 'waterbeetles.geojson' > Export
   2. File type = .geojson
   3. Don't save 'name' column
   4. Specify Date as Date/Time format
6. Visualise your layer
   1. Categories: Families
   2. Quantitative: ?Date
7. 

## Import your GPS locations
*xx minutes*, included in the live session if you attend

The main aim of today is to import your GPS locations into your QGIS project.  We assume that you have already downloaded the WPT (waypoints) file from your GPS, or prepared a spreadsheet containing X and Y coordinates

We anticipate that your location data may be in one of several different formats:
1. If your locations are in `.gpx` file format, as **downloaded from a GPS**, go to the [Importing .gpx](#gpx) section below
2. If you have a **spreadsheet** e.g. `.txt` or `.csv `containing *only* locations, go to the [Importing .txt](#gpx) section below
3. If you have a single file with **locations *and* field data combined**, go to the [Combined data](#combined) section below


Remember that you can always as for assistance in the :raised_hand: [**Help Area**](https://padlet.com/VerdantLearn_LT/GISRefresher2_HelpArea_May2021) for this course if you get stuck


### Importing .gpx
{: #gpx }

**Instructions**

### Importing .txt
{: #txt }

If your location data are in a spreadsheet format, please ensure they are saved as *tab-delimited* spreadsheets (**.txt**), where columns are separated by a tab character.  We will use tab-delimited instead of comma-delimited (.csv = columns separated by a comma) to avoid any complications in regions where commas are used to indicate decimal places, or thousands.  If you're comfortable working with .cvs files then you can choose to work with that format instead

### Combined data
{: #combined }

You're in luck!  :sweat_smile:  As you have a single file containing your location data and field observations combined, you can complete the work for Monday, Tuesday *and* Wednesday in a single step!

See [Importing combined data]({% link modules/Resources/_posts/2000-01-01-field-obs-wpts.md %}) in the Resources section for instructions


